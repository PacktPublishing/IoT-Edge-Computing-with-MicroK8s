# IoT Edge Computing with MicroK8s

<a href="https://www.packtpub.com/product/iot-edge-computing-with-microk8s/9781803230634?utm_source=github&utm_medium=repository&utm_campaign=9781803230634"><img src="https://static.packt-cdn.com/products/9781803230634/cover/smaller" alt="Early Access" height="256px" align="right"></a>

This is the code repository for [IoT Edge Computing with MicroK8s](https://www.packtpub.com/product/iot-edge-computing-with-microk8s/9781803230634?utm_source=github&utm_medium=repository&utm_campaign=9781803230634), published by Packt.

**A hands-on approach to building, deploying, and distributing production-ready Kubernetes on IoT and Edge platforms**

## What is this book about?
Are you facing challenges with developing, deploying, monitoring, clustering, storing, securing, and managing Kubernetes in production environments as you're not familiar with infrastructure technologies? MicroK8s - a zero-ops, lightweight, and CNCF-compliant Kubernetes with a small footprint is the apt solution for you. 

This book covers the following exciting features:
* Get a holistic view of MicroK8s features using a sample application
* Understand IoT and edge computing and their architecture constraints
* Create, scale, and update HA Raspberry Pi multi-node clusters
* Implement AI/ML use cases with the Kubeflow platform
* Work with various networking plugins, and monitoring and logging tools
* Perform service mesh integrations using Istio and Linkerd
* Run serverless applications using Knative and OpenFaaS frameworks
* Secure your containers using Kata and strict confinement options

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1803230630) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter 01.

A block of code is set as follows:
```
apiVersion: v1
kind: Service
metadata:
  name: metallb-load-balancer
spec:
  selector:
    app: whoami
  ports:
    - protocol: TCP
      port: 80
      targetPort: 80
type: LoadBalancer
```

Any command-line input or output is written as follows:

<pre><code><b> kubectl apply -f loadbalancer.yaml </b></code></pre>


**Following is what you need for this book:**
This book is for DevOps and cloud engineers, SREs, and application developers who want to implement efficient techniques for deploying their software solutions. It will also be useful for technical architects and technology leaders who are looking to adopt cloud-native technologies. A basic understanding of container-based application design and development, virtual machines, networking, databases, and programming will be helpful for using this book.

With the following software and hardware list you can run all code files present in the book (Chapter 1-16).
### Software and Hardware List

<table>
			<tr>
				<th>Software/hardware covered in the book</th>
				<th>Operating system requirements</th>
			</tr>
			<tr>
				<td>
        <ul>
          <li>A microSD card (4 GB minimum, with 8 GB recommended)
          <li>A computer with a microSD card drive
          <li>A Raspberry Pi 2, 3, or 4 (3 or more)
          <li>A micro-USB power cable (USB-C for the Pi 4)
          <li>A Wi-Fi network or an Ethernet cable with an internet connection
          <li>(Optional) A monitor with an HDMI interface
          <li>(Optional) An HDMI cable for the Pi 2 and 3 and a micro-HDMI cable for the Pi 4
          <li>(Optional) A USB keyboard
          <li>An SSH client such as PuTTY
          <li>A hypervisor such as Oracle VM VirtualBox 6.1 to create virtual machines
        </ul>
        </td>
				<td>Windows or Linux to run Ubuntu</td>
			</tr>
</table>



We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://packt.link/HprZX).

### Related products
* The Kubernetes Bible [[Packt]](https://www.packtpub.com/product/the-kubernetes-bible/9781838827694?utm_source=github&utm_medium=repository&utm_campaign=9781838827694) [[Amazon]](https://www.amazon.com/dp/1838827692)

* The Kubernetes Operator Framework Book [[Packt]](https://www.packtpub.com/product/the-kubernetes-operator-framework-book/9781803232850?utm_source=github&utm_medium=repository&utm_campaign=9781803232850) [[Amazon]](https://www.amazon.com/dp/1803232854)

## Get to Know the Author
**Karthikeyan Shanmugam**
is an experienced solutions architect professional, with about 20+ years of experience in the design and development of enterprise applications across various industries. Currently, he is working as a senior solutions architect at Amazon Web Services, where he is responsible for designing scalable, adaptable, and resilient architectures that solve client business challenges. Prior to that, he worked for companies such as Ramco Systems, Infosys, Cognizant, and HCL Technologies.
He specializes in cloud, cloud-native, containers, and container orchestration tools, such as Kubernetes, IoT, digital twin, and microservices domains, and has obtained multiple certifications from various cloud providers.
He is also contributing author in leading journals such as InfoQ, Container Journal, DevOps.com, The New Stack, and the Cloud Native Computing Foundation (CNCF.io) blog.
His articles on emerging technologies (including the cloud, Docker, Kubernetes, microservices, and cloud-native development) can be read on his blog at upnxtblog.com.
