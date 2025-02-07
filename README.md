# CCR Bonus Task

This task is based on the PyTorch examples available in [this repository](https://github.com/pytorch/examples/tree/main/mnist). The version provided here includes a few extra print statements.

## Prerequisites

Before starting this task, ensure you have finished setting up your account as described in the [CCR Guide](https://ubuffalo-my.sharepoint.com/:w:/g/personal/avereshc_buffalo_edu/EeI6Blf_ucROmMS9nzeoFPIBZ3T_unSEJBuS2R1jr-HK_A).  

### Important Notes:
- **Do NOT install PyTorch or TensorFlow yourself.**  
  Instead, load the modules using **EasyBuild** as instructed in Section 3.4.2 of the CCR Guide.
- If you install the libraries manually:
  - **GPU usage will not be enabled.**
  - These libraries will consume significant storage on your account, which is limited to **10GB**. (The preinstalled CUDA-enabled libraries are optimized for CCR usage.)

### Why Use EasyBuild?
Using EasyBuild ensures:
- Access to preinstalled, CUDA-enabled PyTorch and TensorFlow libraries.
- Optimal performance on CCR GPUs.
- Efficient use of your allocated storage space.

---

## Instructions

### Choosing the Correct File

There are two files provided in this repository:
1. **`MNIST.py`**  
   Use this file if you are running the task on a **Desktop** or in a **VSCode session**.  

2. **`MNIST.ipynb`**  
   Use this file if you are running the task in a **Jupyter Notebook session**.  

### Steps

1. **Set up your CCR environment**  
   Follow the steps in the CCR Guide to configure your account and load the necessary modules for GPU usage (Section 3.4.2).  

2. **Run the appropriate script**  
   Execute `MNIST.py` or `MNIST.ipynb` depending on your session type.  

3. **Verify GPU Usage**  
   The script should print the device being used.  
   - If the device is **`cuda`**, the GPUs are successfully configured.  
   - If the device is **`cpu`**, your setup is incorrect. Retrace your steps from Section 3.4.2 of the CCR Guide to fix any issues.  

4. **Take a Screenshot**  
   - Scroll to the **end of the output** after running the script.  
   - Ensure the following are visible in your screenshot:
     - **Loss**
     - **Accuracy**
     - **Device being used (should display `cuda`)**
     - **Your ubit name**: For VSCode and Desktop users it should show your ubitname in the terminal itself Eg ubitname@cpn-hi5-xyz. For Notebook users, there is an extra whoami command at the end of the notebook. Make sure it's output is visible.
   - The screenshot should clearly show that you're running the task on CCR.  

5. **Submit the Screenshot**  
   Complete a quiz on UBlearns > Quizzes > [Bonus] CCR before the due date

---

If you encounter any issues during the setup or while running the script, double-check the steps in the CCR Guide or seek assistance on Piazza. Ensure that you are using the GPUs for the bonus task to be considered complete.
