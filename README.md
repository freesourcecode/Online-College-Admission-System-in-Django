# Online College Admission System in Django with Source Code

The **Online College Admission System in Django created based on Python, Django, and SQLITE3 Database**.

When you first visit our website, you will be directed to our homepage’s registration page.

You must provide all of your educational information, including your educational qualifications and extracurricular activities.

An **Online College Admission System in Django** is an easy project for beginners to learn how to build a web-based python Django project.

We will provide you with the complete source code and database for the python project so that you can easily install it on your machine and learn how to program in Python Django.

>[!NOTE]
> To start creating an **Online College Admission System Project in Python Django**, makes sure that you have PyCharm Professional IDE Installed in your computer.

## Admin Features

* **Dashboard**

In this page, the admin can see all the features of the system.

* **Login Page**

The page where the system administrator enters their system credentials in order to gain access to the system’s administrative side.

* **Manage Contact**

This is the page where an administrator can view all the customers who submit their message to the admin.

* **Manage Colleges**

This is the page where an administrator can add, update, view and delete colleges information.

* **New User Page**

The page where a new admin credentials are created by an admin.

* **Users list**

This is the page that lists and manages the added users.

## User Features

* **Dashboard**

In this page, user can see the status of his application form, chmsc campuses.

*  **Register Page**

The page where new user created their login credentials for the website.

*  **Login Page**

The page where the system administrator enters their system credentials in order to gain access to the system’s administrative side.

* **Admission Form Page**

In this page, user can fill the form and check his / her application form is selected or rejected(which is done by admin).

*  **View Colleges**

This is the page where the user can view all the chmsc campuses.

##  Online College Admission System in Django Steps on How to Create a Project

Here are the steps on how to create a **Django Online College Admission System with Source Code**.

1. **Open file**.

Open "pycharm professional" after that click "file" and click "new project".

2. **Choose Django**.

Next, after click "new project", choose "Django" and click.

3. **Select file location**.
Then, select a file location wherever you want.

4. **Create application name**.

After that, name your application.

5. **Click create**.
Finish creating project by clicking “create” button.

6. **Start Coding**.

Finally, we will now start adding functionality to our Django Framework by adding some functional codes.

## Functionality and Codes

* Create template for the homepage in **Online College Admission System Project in Django**.

In this section, we will learn on how create a templates for the homepage. To start with, add the following code in your index.html under the folder of /templates/.

```{% extends 'base.html' %}

{% block title %}Home{% endblock title %}

{% block body %}

<div class="container {% comment "" %} my-4 {% endcomment %}">
<div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
    <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="/static/img/tal.jpg" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block"  style="background: black;  border-radius: 21px;">
        <h5>Welcome To CHMSC</h5>
        <p>This is the best platform for admission</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="/static/img/talisay.jpg" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block"   style="background: black;  border-radius: 21px;">
        <h5>Select Your Best College</h5>
        <p>This platform serves the best colleges of CHMSC</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="/static/img/tali.jpg" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block"  style="background: black;  border-radius: 21px;">
        <h5>Start making future</h5>
        <p>Take admission and keep first step to your goal</p>
      </div>
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
</div>


<div class="container my-3">
<h1 class="my-3 text-center">Select College According to Your Criteria</h1>

      <div class="row">
        <div class="col-md-4">
          <div class="card mb-4 shadow-sm">
              <img src="/static/img/bin.jpg" class="d-block w-130" alt="...">            
              <div class="card-body">
              <p class="card-text">Bachelor of Science in Criminology (BS Crim)
Bachelor of Secondary Education (BSED) major in Biological Science; Physical Science; Science;Technology and Livelihood Education
Bachelor of Elementary Education (BEED) major in General Education
Bachelor of Science in Fisheries (BSF)
Bachelor of Science in Industrial Technology (BSIT) major in Computer Technology</p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
                  <button type="button" class="btn btn-sm btn-outline-secondary">View</button>
                  <button type="button" class="btn btn-sm btn-outline-secondary">Edit</button>
                </div>
                <small class="text-muted">9 mins</small>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card mb-4 shadow-sm">
              <img src="/static/img/fortune.jpg" class="d-block w-100"  alt="...">
              <div class="card-body">
              <p class="card-text">CHMSC Fortune Towne shall strive to provide quality services to its clientele (academic community) in the areas of research instructi on, extension and production.</p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
                  <button type="button" class="btn btn-sm btn-outline-secondary">View</button>
                  <button type="button" class="btn btn-sm btn-outline-secondary">Edit</button>
                </div>
                <small class="text-muted">9 mins</small>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card mb-4 shadow-sm">
            <img src="/static/img/aljis.jpg" class="d-block w-100" alt="...">
            <div class="card-body">
              <p class="card-text">CHMSC Alijis Campus aims to provide and implement programs and projects along teacher education, technology and other areas in developing world </p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
                  <button type="button" class="btn btn-sm btn-outline-secondary">View</button>
                  <button type="button" class="btn btn-sm btn-outline-secondary">Edit</button>
                </div>
                <small class="text-muted">9 mins</small>
              </div>
            </div>
          </div>
        </div>

  
      </div>
    </div>
{% endblock body %}

```
### 📌 Here's the full documentation for the [Online College Admission System](https://itsourcecode.com/free-projects/django/online-college-admission-system-project-in-django-with-source-code/)




        


