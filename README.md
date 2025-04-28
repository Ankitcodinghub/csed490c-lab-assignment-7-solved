# csed490c-lab-assignment-7-solved
**TO GET THIS SOLUTION VISIT:** [CSED490C Lab Assignment 7 Solved](https://www.ankitcodinghub.com/product/csed490c-lab-assignment-7-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115725&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSED490C Lab Assignment 7 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1 Objective

The purpose of this lab is to implement a kernel that performs sparse matrix-vector multiplication on a transposed JDS (Jagged Diagonal Sparse) format. Please refer to the lectures notes (slide 40 to 45) on how JDS format with transposition works. You should change the data layout of a sparse matrix in the dense matrix format first to transposed JDS format first on the host, perform matrix-vector multiplication on GPU, then convert the result back to a dense matrix to verify the result on the host.

2 Instructions

Edit the skeleton code to perform the following:

• Allocate device memory

• Copy host memory to device

• Initialize thread block and kernel grid dimensions

• Invoke CUDA kernel

• Copy results from device to host

• Deallocate device memory

• Write the CUDA kernel

Compile the template with the provided Makefile. The executable generated as a result of compilation can be run using the following code:

./JDS T Template -e &lt;expected.raw&gt; -i &lt;input0.raw&gt;,&lt;input1.raw&gt; -o &lt;output.raw&gt;

-t vector

where &lt;expected.raw&gt; is the expected output, &lt;input0.raw&gt; and &lt;input1.raw&gt; is the input dataset (input0.raw is the sparse matrix, and input1.raw is the input vector), and &lt;output.raw&gt; is an optional path to store the results.

README.md has details on how to build libgputk, template.cpp and the dataset generator.

3 What to Turn in

Submit a report that includes the following:

1. Two versions of template.cpp with and without shared memory staging (bringing data into shared memory for computation and writing back at the end)

2. The result as a table/graph of kernel execution times for different input data, with the systeminformation where you performed your evaluation. Run your implementation with the input generated by the provided dataset generator. For time measurement, use gpuTKTime start and gpuTKTime stop functions (You can find details in libgputk/README.md).
