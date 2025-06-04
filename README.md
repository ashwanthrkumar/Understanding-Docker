<h1 align="center" id="title">Understanding Docker</h1>

<p align="center"><img src="https://socialify.git.ci/ashwanthrkumar/Understanding-Docker/image?custom_description=This+is+a+beginner-friendly+project+designed+to+help+you+understand+the+basics+of+Docker+by+containerizing+a+simple+Python+Flask+application.+This+project+demonstrates+how+to+package+a+web+app+into+a+Docker+image%2C+run+it+in+an+isolated+container%2C+and+expose+it+on+a+port+to+access+it+via+a+web+browser.&amp;description=1&amp;font=Inter&amp;language=1&amp;name=1&amp;owner=1&amp;pattern=Solid&amp;theme=Light" alt="project-image"></p>


<h2>🛠️ Installation Steps:</h2>

<p>1. Clone this repo</p>

```
git clone https://github.com/ashwanthrkumar/Understanding-Docker.git
```

<p>2. Enter into the directory</p>

```
cd Understanding-Docker
```

<p>3. Make sure you have installed Docker</p>

```
docker --version
```

<p>4. If docker not found download from</p>

```
https://www.docker.com/
```

<p>5. Now build your docker image (I have given mine as hello-docker you can give your own)</p>

```
docker build -t hello-docker .
```

<p>6. Run the Container</p>

```
docker run -p 5000:5000 hello-docker
```

<p>7. Visit in browser</p>

```
http://localhost:5000
```

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   Python
*   Docker
