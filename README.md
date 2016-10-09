# Git 101
### Must-know skill for CS peeps
---

# Agenda

1. Setup
  - Create [github.com](github.com) account
  - Install [GitHub Desktop](https://desktop.github.com/)
1. Introduction to Version Control System
1. **Why** we need to use GitHub
1. **How** to use Git & GitHub
  1. Create
      - create repository on GitHub (README.md - markdown syntax)
      - clone repo to local (remote vs local)
  1. Edit
      - stage files
        -.gitignore
      - commit to local repo
      - see changelog & snapshots
      - push
  1. Collaborate
      - branch (off-topic: create blog with GitHub)
      - 

---

# Setup

---
# Setup
Let's dive in head first.

1. Create [github.com](github.com) account
1. Install [GitHub Desktop](https://desktop.github.com/)
  - Advanced users may prefer to use command lines
  - At the end of the presentation, I'll tell you potentially better apps.
  - Linux users can use [GitKraken](https://www.gitkraken.com/download)

---

### While you do that,
#VCS: version control system

---
# Version Control System

> Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later... in reality you can do this with nearly any type of file on a computer. If you are a graphic or web designer and want to keep every version of an image or layout (which you would most certainly want to), a Version Control System (VCS) is a very wise thing to use... Using a VCS also generally means that if you screw things up or lose files, you can easily recover. In addition, you get all this for very little overhead.

1. revert files back to a previous state
2. revert the entire project back to a previous state
3. compare changes over time
4. see who last modified something that might be causing a problem
5. who introduced an issue and when, and more. 


---
# Learn More
Advanced Git apps: [SourceTree](https://www.sourcetreeapp.com/), [GitKraken](https://www.gitkraken.com/)
[GitHub intro page](https://guides.github.com/activities/hello-world/)
[GitHub flow tutorial](https://guides.github.com/introduction/flow/)
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
[Create a blog/website with GitHub](https://jekyllrb.com/)
[Learn git with command lines](http://learngitbranching.js.org/)



######소스저장소란, 

######버젼관리시스템(VCS, Version Control System)의 이점
1. 변경된 내용을 공유 가능 - 어떤 생각으로, 어떤 과정 등
1. 타인이 작업한 내용 쉽게 병합 - 협업 가능
1. 과거 상태로 복구 가능
1. 여러 분기(Branch)를 통해 병렬 관리 가능

######Examples of VCS
1. Subversion (SVN) - Git과 함께 가장 대표적으로 사용되고 Git 이전에는 대부분 SVN을 사용함. Git과 다르게 원격저장소만 있음.
1. Mercurial - Git과 비슷한 철학; 가볍고 쉬운 사용을 위해 탄생함.
1. Git by Linus Torvalds (also made Linux)
	1. 복잡한 *Branch* 관리 적합
	1. 로컬과 원격 저장소의 분리
	1. 다양한 서비스 업체 like GitHub
	1. 다양한 보조 툴

#####Git
######Git Flow
1. Working Directory - where we actually work on the file (local computer?)
1. Stage Area - Stage fixes. we prepare today's work for Git. We check which files to commit and leave comments.
1. .git directory (Repository) - Commit. like a Photoshop snapshot. 
1. Remote Repository

######Repository 
Git leaves same files in Local as well as Remote Repository. Local works even where user has limited internet access. So if there's no need to share a project, there's no need to sync with Remote Repository. Remote Repository is the repository in the traditional sense. It is where change is logged. Meeting place of all local repositories. 

######Why Stage Area?
So that you can choose which files to commit. For example, when the client doesn't want the new function but wants the security patch. Or when there are files that are not related to the product, such as IDE-dependent files or OS-dependent files. You can manage these with .gitignore file. 

#####SourceTree
Another Git program. You can Push (copy from your local repo to remote repo) or Pull (copy from remote repo to local repo). If there are unwanted files, you can use .gitignore: open it in a text editor and write the filenames. 
![GitFlow - Branching and Merging](http://jeffkreeftmeijer.com/images/gitflow.gif)
You can branch or merge to cooperate effectively.
<!-- Master branch -->
I am continuously developing on the master branch. 
This is some new information.
<!-- New feature called sausage -->
sausage has slices
it is one big chunk.
<!-- feature/bun -->
this is a new feature on our hotdog called a bun.
Buns are usually made of sandwich shaped bread.
But they can also be made of other things, if you want to become creative.
For example, KFC has a menu called Double Down MAX, which has chicken breasts as the buns.
<!-- inside the bun -->
inside the bun, usually there is a sausage or patty.
Generally, a sausage is long and round like a dick; 
a patty is round and flat like a pancake.
<!-- smg 브랜치에서 작성 -->
