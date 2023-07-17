How to build a CI/CD pipeline with GitHub Actions 

CI = continuous integration 
CD = continuous delivery 

สวัสดีครับ เมื่อต้องการรวม Source Code กับคนในทีมและนี้คือวิธีหนึ่งที่ประหยัดเวลาที่สุดครับ

ก่อนอื่น  GitHub Action คืออะไร  เป็นเครื่องมือหนึ่งที่ ช่วยทำให้การทำ CI/CD ง่ายขึ่น โดยมี Workflow สำหรับนำ Source code บน Github ไปดำเนินการต่อ  push , pull requerst , merged code  ซึ่ง Work flow ประกอบด้วย หลายๆ Action เรียงกันไป แต่ว่า Action ไม่สามารถ trigger Action ของ อีกอันได้ ตัวอย่างคือ เมื่อมีคน push เข้ามาที่ branch main ก็ให้ Deploy ไปที่ Host ที่เราต้องการโดยอัตโนมัติ  







reft: 1.https://www.selfhost.life/cicd-with-github-action-and-runner/
      2.https://cloud-ace.co.th/blogs/b3q9s1-ci-cd-github-actions-cloud-build
      3.Action https://github.com/marketplace 
      4.https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions


https://nakorndev.github.io/cheatsheet-git-graph/
[Git For Orix Team.pdf](https://github.com/sarwanputeh/CI-CD-pipeline-with-GitHub-Actions/files/12067114/Git.For.Orix.Team.pdf)
