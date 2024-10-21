# A quick way to run small RAxML analyses in a GitHub Codespace

## To launch: click the "<>Code" button

![Screenshot of launching a Codespace](https://github.com/user-attachments/assets/757a1acc-4541-478b-9059-3d946d7eb644)

By default, the Codespace will launch with only 2-cores. If you want more, click the 3-dot menu and select "New with options".

![Screenshot of new with options option in the 3-dot menu](https://github.com/user-attachments/assets/9473246e-db9a-429c-a39c-2f3221b3f13a)

In the screen that comes up, select the number of cores you want. **The 16-core machine is not allowed.**
![Screenshot of resource selection](https://github.com/user-attachments/assets/5fbf0414-d65b-49b8-ae3a-7fad7415ee18)

## Boot process

The Codespace will boot and install RAxML.
Once it is done, you will see a command prompt.

## Open a Bash terminal and run RAxML

**Do not use the sh terminal that remains open from the boot process. Close that and open a Bash terminal.**

Open a Bash terminal:
![Screenshot of opening a Bash terminal](https://github.com/user-attachments/assets/0b48e5d3-dbf7-4cd7-9a0b-bfb53a19ca3f)

Type your RAxML command. For the help documentation, type `raxmlHPC-PTHREADS-AVX2 -h`
![image](https://github.com/user-attachments/assets/3a7cf938-83ea-4af8-8e5b-069879a70f5b)

## Upload your dataset

Drag and drop your dataset into the File explorer to upload.


