# 2024-dj-medium-clone-turki
Compiling the source code by git commit

#### 1. Initial commit

        modified:   README.md
        new file:   config/__init__.py
        new file:   config/asgi.py
        new file:   config/settings.py
        new file:   config/urls.py
        new file:   config/wsgi.py
        new file:   manage.py
        new file:   requirements.txt


#### 2. Home_view-Added-and-Settings-Updated

        modified:   README.md
        modified:   config/settings.py
        modified:   config/urls.py
        new file:   front_end_html_files/css/style.css
        new file:   front_end_html_files/index.html
        new file:   page/__init__.py
        new file:   page/admin.py
        new file:   page/apps.py
        new file:   page/migrations/__init__.py
        new file:   page/models.py
        new file:   page/templates/page/home_page.html
        new file:   page/tests.py
        new file:   page/views.py
        new file:   static_files/css/bootstrap.min.css
        new file:   static_files/css/bootstrap.min.css.map
        new file:   static_files/css/style.css
        new file:   static_files/js/bootstrap.bundle.min.js
        new file:   static_files/js/bootstrap.bundle.min.js.map


#### 3. Settings-In-Settings-of-Home-Page-and-Static-Files-Arrangements

        modified:   README.md
        modified:   config/settings.py
        modified:   page/templates/page/home_page.html
        new file:   templates/core/base.html
        new file:   templates/core/footer.html
        new file:   templates/core/navbar.htmlb


#### 4. Transfer-TODO-List-To-Do-In-Project

        modified:   README.md
        modified:   config/settings.py


#### 5. Creating-the-login-html-structure-and-Adding-the-Login-Form

        new file:   blog/__init__.py
        new file:   blog/admin.py
        new file:   blog/apps.py
        new file:   blog/migrations/__init__.py
        new file:   blog/models.py
        new file:   blog/tests.py
        new file:   blog/views.py
        modified:   config/settings.py
        modified:   config/urls.py
        new file:   templates/core/base_without_navbar.html
        new file:   user_profile/__init__.py
        new file:   user_profile/admin.py
        new file:   user_profile/apps.py
        new file:   user_profile/migrations/__init__.py
        new file:   user_profile/models.py
        new file:   user_profile/templates/user_profile/login.html
        new file:   user_profile/tests.py
        new file:   user_profile/urls.py
        new file:   user_profile/views.py


#### 6. Checking-Login-Information-With-Authenticate

        modified:   README.md
        modified:   config/settings.py
        modified:   user_profile/views.py


#### 7. Informing-the-User-who-Login-With-Django-Messages-Framework

        modified:   templates/core/base.html
        new file:   templates/core/messages.html
        modified:   user_profile/views.py


#### 8. Informing-the-User-who-Login-With-Django-Messages-Framework

        modified:   templates/core/messages.html


#### 9. Creating-Logout-View-and-Adding-Urls-e 

        modified:   user_profile/urls.py
        modified:   user_profile/views.p


#### 10. Adding-Login-Controls

        modified:   templates/core/base_without_navbar.html
        modified:   user_profile/views.py


#### 11. Creating the Sign-Up-Register-Page

        modified:   config/settings.py
        modified:   templates/core/navbar.html
        new file:   user_profile/templates/user_profile/register.html
        modified:   user_profile/urls.py
        modified:   user_profile/views.py


#### 12. Creating-User-Profile-Model-Structure

        modified:   user_profile/models.py
        modified:   user_profile/templates/user_profile/register.html
        modified:   user_profile/views.py


#### 13. Performing-Controls-in-Register-View

        modified:   user_profile/views.py


#### 14. Checking-Whether-The-User-Who-Wants-To-Be-Registered-Has-Been-Registered Before

        modified:   user_profile/views.py


#### 15. Writing-User-Information-to-Profile-Model

        new file:   avatar/melinda-gimpel-5Ne6mMQtIdo-unsplash.jpg
        new file:   avatar/melinda-gimpel-5Ne6mMQtIdo-unsplash_1TOVWwE.jpg
        modified:   user_profile/admin.py
        modified:   user_profile/models.py
        modified:   user_profile/views.py


#### 16. Setting-Media-Files-Settings

        modified:   config/settings.py
        modified:   config/urls.py


#### 17. abstract-creating-blog-model-information-with-model-structure 

        modified:   blog/models.py
        modified:   config/settings.py


#### 18. Creating-Blog-Post-Create-Structure-With-ModelForm

        new file:   blog/forms.py
        new file:   blog/templates/blog/create_blog_post.html
        new file:   blog/urls.py
        modified:   blog/views.py
        modified:   config/urls.py
        modified:   templates/core/base.html


#### 19. Editing-the-HomePage-and-Adding-Class-to-Form-Structure

        modified:   blog/forms.py
        modified:   blog/templates/blog/create_blog_post.html
        modified:   page/templates/page/home_page.html
        modified:   templates/core/base.html


#### 20. Editing-BlogPost-Name-and-Form-Editing

        modified:   blog/admin.py
        modified:   blog/forms.py
        modified:   blog/models.py
        modified:   blog/templates/blog/create_blog_post.html
        modified:   blog/views.py
        modified:   config/settings.py


#### 21. Project4: Editing-BlogPost-Name-and-Form-Editing

		NOTE: Nothing changed!


#### 22. Registering-and-Using-TinyMCE-of-PostModelForm

        modified:   blog/forms.py
        modified:   blog/templates/blog/create_blog_post.html
        modified:   blog/views.py
        modified:   config/settings.py
        modified:   requirements.txt
        new file:   static_files/js/tinymce.min.js


#### 23. Registering-and-Using-TinyMCE-of-PostModelForm

        modified:   blog/views.py


#### 24. Form-Validators-Usages

        modified:   blog/forms.py
        modified:   blog/urls.py
        modified:   blog/views.py


#### 25. Adding-Tagify-to-Form-Structure

        modified:   blog/templates/blog/create_blog_post.html
        modified:   blog/views.py
        new file:   static_files/css/tagify.css
        new file:   static_files/js/tagify.js
        new file:   static_files/js/tagify.polyfills.min.js


#### 26. Creating-To-Many-Form-Structure-When-Adding-Tags-And-Working-With-Django-Extensions

        modified:   blog/views.py
        modified:   config/settings.py
        modified:   requirements.txt


#### 27. Saving-the-Form-and-Transmitting-Message-To-The-User-To-Return-To-The-Home-Page

        modified:   blog/views.py


#### 28. Making-Posts-Visible-on-HomePage-and-Easy-Using-Thumbnail

        new file:   blog/templates/blog/components/post.html
        modified:   blog/views.py
        modified:   config/settings.py
        modified:   page/templates/page/home_page.html
        modified:   page/views.py
        modified:   requirements.txt


#### 29. Adding-Ordering-to-Model-Structure-and-Home-Page-Edits

        modified:   blog/models.py
        modified:   blog/views.py
        modified:   page/templates/page/home_page.html
        modified:   page/views.py


#### 30. Showing-All-User-Texts

        modified:   config/settings.py
        modified:   config/urls.py
        new file:   read/__init__.py
        new file:   read/admin.py
        new file:   read/apps.py
        new file:   read/migrations/__init__.py
        new file:   read/models.py
        new file:   read/templates/read/all_posts.html
        new file:   read/tests.py
        new file:   read/urls.py
        new file:   read/views.py
        modified:   templates/core/navbar.html
        modified:   user_profile/views.py
