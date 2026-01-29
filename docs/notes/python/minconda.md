## miniconda install error
1. Error description  

    ```bash
    conda activate llm
    CondaError: Run 'conda init' before 'conda activate'
    ```

2. reason  
    In windows,when use git bash. run sh.exe to open terminal,it will not load ~/.bash_profile.
    so it not work.  

3. solution  

 - open sh with login: `sh --login `
 - add `source ~/.bash_profile` into `bash.bashrc`.but sh terminal open very slow.
