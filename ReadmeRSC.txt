12/2/2019 - Cloned from Githib
This is a clone from Github. I did this beause the original local branch
(in djangogirls folder) has some testing changes that I don't want to pollute
the working PA branch. So, this is the PA branch.
Note that the highest-level /static is not present as it is in .gitignore list.

To create a clone, I did the following:
1. Log into Github (as ScottCooper520).
2. Navigate to desired repo (my-first-blog)
3. Click on the Clone or download button.
   => This will show a url: https://github.com/ScottCooper520/my-first-blog.git
4. Now from UbuntuDesktop, open terminal in desired folder to copy repo into.
5. Type: git clone https://github.com/ScottCooper520/my-first-blog.git
6. Done.

11/19/2019
This is an end-to-end working example from djangogirls tutorial.
I am now going to extend this example to include the ability to upload and display 
images. The original working example is backed up as djangogirls_gf.

Main changes I am making:
pip install pillow (from myvenv). Pillow required for ImageField()
=> Successfully installed pillow-6.2.1

Update blog/models.py to include imagefield.

activate mvenv:
source myvenv/bin/activate

If I lose django admin password, can always generate a new one
(myvenv) python manage.py createsuperuser

