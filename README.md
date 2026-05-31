# Ex08 CAMU Schedule using Bootstrap
## Name : T.Rishabh srivastav
## Reg : 212224113001
## Date:

## AIM:
To design a responsive and visually appealing CAMU Schedule using Bootstrap.

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Add the Bootstrap CDN link inside the ```<head>``` section.

### Step 5:
Insert a table element with Bootstrap table classes.

### Step 6:
Construct the complete table.

### Step 7:
Add a header/footer displaying copyright information.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM :

~~~
<!DOCTYPE html>
<html>
<head>
    <title>T.Rishabh srivatsav</title>

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body class="bg-light">

    
    <div class="bg-primary text-white text-center p-3">
        <h2>SLOT TIME TABLE</h2>
        <p>T.Rishabh srivatsav(212224113001)</p>
    </div>

    <div class="container mt-4 text-center">

        
        <img src="logo.png" class="img-fluid mb-3" width="400">

       
        <table class="table table-bordered table-striped table-hover">
            <caption class="fw-bold">Weekly Schedule</caption>

            <thead class="table-dark">
                <tr>
                    <th>Day/Time</th>
                    <th>Monday</th> 
                    <th>Tuesday</th>
                    <th>Wednesday</th>
                    <th>Thursday</th> 
                    <th>Friday</th>
                    <th>Saturday</th>
                </tr>
            </thead>

            <tbody>
                <tr class="table-warning">
                    <td>8-10</td>
                    <td>EVS</td>
                    <td colspan="5">FS</td>
                </tr>

                <tr class="table-info">
                    <td>10-12</td>
                    <td>MAI</td>
                    <td>BEEE</td>
                    <td>FS</td>
                    <td>BEEE</td>
                    <td>FS</td>
                    <td>MAI</td>
                </tr>

                <tr class="table-danger text-center">
                    <td>12-1</td>
                    <td colspan="6"><b>LUNCH BREAK</b></td>
                </tr>

                <tr class="table-primary">
                    <td>1-3</td>
                    <td>BEEE</td>
                    <td>EVS</td>
                    <td>MAI</td>
                    <td>BEEE</td>
                    <td>EVS</td>
                    <td>FS</td>
                </tr>

                <tr class="table-warning">
                    <td>3-5</td>
                    <td colspan="2">FS</td>
                    <td colspan="3">MAI</td>
                    <td>FS</td>
                </tr>
            </tbody>
        </table>

        
        <table class="table table-bordered mt-4">
            <thead class="table-secondary">
                <tr>
                    <th>S.NO</th>
                    <th>Subject Code</th>
                    <th>Subject Name</th>
                </tr>
            </thead>

            <tbody>
                <tr>
                    <td>1</td>
                    <td>19CY801</td>
                    <td>Environmental Science and Sustainability (EVS)</td>
                </tr>

                <tr>
                    <td>2</td>
                    <td>19EE305</td>
                    <td>Basic Electrical and Electronics Engineering (BEEE)</td>
                </tr>

                <tr>
                    <td>3</td>
                    <td>19EE404</td>
                    <td>Mathematics for Artificial Intelligence (MAI)</td>
                </tr>
            </tbody>
        </table>

    </div>

    
    <div class="bg-dark text-white text-center p-2 mt-4">
        <p>© 2026 Designed by T.Rishabh srivatsav</p>
    </div>

</body>
</html>
~~~
## OUTPUT:

<img width="1907" height="1077" alt="Screenshot 2026-05-31 125305" src="https://github.com/user-attachments/assets/314a343d-563d-4203-884f-d458117e97d6" />



## RESULT:
A responsive and visually appealing CAMU Schedule web page using Bootstrap is designed successfully.
