# math208---final-project-solved
**TO GET THIS SOLUTION VISIT:** [MATH208 – Final Project Solved](https://www.ankitcodinghub.com/product/math208-final-project-description-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119305&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MATH208 - Final Project Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Background and Introduction

The final project for the course will require you to complete some exploratory analyses based on data from Kaggle on CPU and GPU processors over time. The link to the Kaggle page is below.

https://www.kaggle.com/datasets/michaelbryantds/cpu-and-gpu-product-data (https://www.kaggle.com/datasets/michaelbryantds/cpu-and-gpu-product-data)

I have attached the dataset to the project description on Crowdmark so that you do not have to register for an account. The data on Kaggle is comprised a single CSV file containing data on approximately 5,000 GPUs and CPUs.

library(tidyverse)

cpu_gpu_data&lt;-read_csv(“chip_dataset.csv”) names(cpu_gpu_data)

[1] “ID” “Product” “Type”

[7] “Die Size (mm^2)” “Transistors (million)” “Freq (MHz)”

[10] “Foundry” “Vendor” “FP16 GFLOPS”

[13] “FP32 GFLOPS” “FP64 GFLOPS”

Objectives and evaluation

The completion of each task is worth 35 points. The quality of presentation will also be worth 30 points, i.e. clarity of explanation, plots, tables, and code.

The length of the projects will vary, depending on the number and formatting of figures and tables and the conciseness of the writing. Rather than focusing on the number of pages, I encourage students to focus on completing each task (and subtask) below to the best of their ability in the clearest and most efficient manner.

Tasks to complete

Task 1: Overall summaries of the data

The first task is to provide some exploratory data analyses and describe the distributions of the basic information and of the five physical and performance characteristics and their associations.

a. For CPU’s and GPU’s separately, summarize numerically and graphically each of the five physical and performance characteristics using appropriate summary measures and plots.

Compare the distributions of GPU’s and CPU’s for each measure, i.e. how are they most similar and how are they most different in terms of central location, spread, skew and outliers. Be sure to report on any missing observations as well.

b. Do you see any strong association between the number of processors released by the vendors and the foundries, i.e. do some vendors release semiconductors exclusively from one foundry or vice versa? Does this association depend on whether they are CPU’s or GPU’s? Use both numerical and graphical summaries to support your conclusions. Note: You can (should?) collapse some of the foundries with smaller counts into a single level to facilitate interpretation.

c. Does the association between Die Size and Thermal Design Power depend on Type? Explain your answer both numerically and graphically.

Task 2: Change over time

b. Moore’s Law: Moore originally posited that the number of transistors per microchip would double every two years. Assess whether or not this is true by computing what you would expect to see if Moore’s law held for CPU’s and GPU’s separately and then comparing to what you observe in the data both numerically and graphically (Hint: you can use the average number of transistors per processor per year).
