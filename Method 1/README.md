1. Step one involves changing clothes in 2d using existing algorithms.
2. Download and extract the rar file from "https://drive.google.com/file/d/1ZmoX0qxmiBLNbIjjrhNnsx1hRkHnoz58/view?usp=drive_link" open folder E2E-CVTON and open cmd/powershell at this path.
3. Paste the command "uvicorn api:app --host 127.0.0.1 --port 5000 --reload" in cmd/powershell.
4. Step two involves converting 2d image to 3d mesh, we have used 2 methods PIFUHD and UNIQUE3D to achieve the goal.
5. Currently in step 2 we are using api of Unique3D for conversion of 2D image to 3D mesh which can be accessed using gradio client, instructions mentioned at "http://unique3d.demo.avar.cn/?view=api"
6. Links of research papers for reference:- 1) Unique3D "https://arxiv.org/abs/2405.2034" 2) PIFUHD "https://arxiv.org/abs/2004.00452"
7. PIFUHD is accurate in producing high quality mesh, combining colouring algorithm as mentioned in the Unique3D paper with PIFUHD can give promising results.
