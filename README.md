## **🛠️ Quick Start**  

### **Requirements**  
- Python = 3.8  
- Cython
- sklearn, pandas

Please refer to requirements.txt for more details

### **Installation**  
1. Download source codes from this repository

2. Create the virtual environment

   ```shell
   conda create -n aam python=3.8
   ```

3. Install based on requirements.txt

   ```shell
   pip install -r requirement.txt
   ```

4. Run the our techniques in corresponding directories

   Taking RRSP as an example:

   ```shell
   cd \multiple_request\RRSP\scripts\tests
   python forest1.py --dataset <dataset_name> --file_number <number> --seed <seed_value>
   ```

   demo

   ```shell
   python forest1.py --dataset adult --file_number 1 --seed 42 --model dare
   
   ```

   Please modify the file path based on your specific context.
   
   Note: the ``dare'' library must be well installed. Please refer to [GitHub - jjbrophy47/dare_rf: Machine Unlearning for Random Forests](https://github.com/jjbrophy47/dare_rf)
