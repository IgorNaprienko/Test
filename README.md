# Test

# ������ ���� ���������� Git ��������

# ��������� � ����������� �������
cd project

# ������� ���� Readme c ������� Test
echo "# Test" >> README.md 

# ���������� git
git init

# ��������� ��� ��������  ���� README.md 
git add README.md

#
git commit -m "first commit"

# ������������� ��������� ����������� 

git remote add origin git@github.com:IgorNaprienko/Test.git

# �������� ������
git status
 --
    On branch master
    Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git checkout -- <file>..." to discard changes in working directory)
        modified:   README.md

    no changes added to commit (use "git add" and/or "git commit -a")
# ������� �������� ��������� , ���������    
git 
# ����� 
git push -u origin master



