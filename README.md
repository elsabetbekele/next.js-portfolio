  <h3 align="center">A Modern Next.js Portfolio</h3>

## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- Framer Motion
- Tailwind CSS

## <a name="features">🔋 Features</a>

👉 **Hero**: Captivating introduction featuring a spotlight effect and dynamic background.

👉 **Bento Grid**: Modern layout presenting personal information using cutting-edge CSS design techniques.

👉 **Testimonials**: Dynamic testimonials area with scrolling or animated content for enhanced engagement.

👉 **Work Experience**: Prominent display of professional background for emphasis and credibility.

👉 **Canvas Effect**: Innovative use of HTML5 canvas to create visually striking effects in the "approaches" section.

👉 **Responsiveness**: Seamless adaptability across all devices, ensuring optimal viewing experience for every user.

and many more, including code architecture and reusability

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/elsabetbekele/next.js-portfolio.git
cd portfolio
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Running the Project**

```bash
npm run dev
```

<details>
<summary><code>data/index.ts</code></summary>

import Image from "next/image";

export const navItems = [
{ name: "About", link: "#about" },
{ name: "Projects", link: "#projects" },
{ name: "Testimonials", link: "#testimonials" },
{ name: "Contact", link: "#contact" },
];

export const gridItems = [
{
id: 1,
title: "I value client collaboration and clear communication.",
description: "",
className: "lg:col-span-3 md:col-span-6 md:row-span-4 lg:min-h-[60vh]",
imgClassName: "w-full h-full",
titleClassName: "justify-end",
img: "/b1.png",
spareImg: "",
},
{
id: 2,
title: "I'm very flexible with time zone communications",
description: "",
className: "lg:col-span-2 md:col-span-3 md:row-span-2",
imgClassName: "",
titleClassName: "justify-start",
img: "",
spareImg: "",
},
{
id: 3,
title: "My tech toolkit",
description: "I constantly try to improve",
className: "lg:col-span-2 md:col-span-3 md:row-span-2",
imgClassName: "",
titleClassName: "justify-center",
img: "",
spareImg: "",
},
{
id: 4,
title: "Dedicated to exploring and building with technology.",
description: "",
className: "lg:col-span-2 md:col-span-3 md:row-span-1",
imgClassName: "",
titleClassName: "justify-start",
img: "/grid.svg",
spareImg: "/b4.svg",
},

{
id: 5,
title: "Developing a dynamic JS animation library.",
description: "The Inside Details",
className: "md:col-span-3 md:row-span-2",
imgClassName: "absolute right-0 bottom-0 md:w-96 w-60",
titleClassName: "justify-center md:justify-start lg:justify-center",
img: "/b5.svg",
spareImg: "/grid.svg",
},
{
id: 6,
title: "Do you want to start a project together?",
description: "",
className: "lg:col-span-2 md:col-span-3 md:row-span-1",
imgClassName: "",
titleClassName: "justify-center md:max-w-full max-w-60 text-center",
img: "",
spareImg: "",
},
];

export const projects = [
{
id: 1,
title: "Intellectual Property Registration System",
des: "A modern system designed to streamline the registration and management of intellectual property rights efficiently.",
img: "/int.png",
iconLists: ["/re.svg", "/tail.svg", "/ts.svg", "/three.svg", "/fm.svg"],
link: "https://eipa.gov.et",
},
{
id: 2,
title: "Yoom - Video Conferencing App",
des: "Simplify your video conferencing experience with Yoom. Seamlessly connect with colleagues and friends.",
img: "/p2.svg",
iconLists: ["/next.svg", "/tail.svg", "/ts.svg", "/stream.svg", "/c.svg"],
link: "https://github.com/adrianhajdin/zoom-clone",
},
{
id: 3,
title: "AI Image SaaS - Canva Application",
des: "A REAL Software-as-a-Service app with AI features and a payments and credits system using the latest tech stack.",
img: "/p3.svg",
iconLists: ["/re.svg", "/tail.svg", "/ts.svg", "/three.svg", "/c.svg"],
link: "https://github.com/adrianhajdin/ai_saas_app",
},
{
id: 4,
title: "Modernizing Cottex Apparel",
des: "Enhancing the Cottex Apparel platform with modern technologies to streamline e-commerce and improve user experience.",
img: "/p4.svg",
iconLists: ["/next.svg", "/tail.svg", "/ts.svg", "/three.svg", "/gsap.svg"],
link: "https://github.com/elsabetbekele/modernizing-cottex-apparel",
},
];

export const testimonials = [
{
quote:
"Elizabeth's attention to detail and problem-solving skills transformed our project. Her ability to understand our needs and deliver beyond expectations was truly impressive.",
name: "Sarah Thompson",
title: "CEO of Innovate Solutions",
image: "/sarah.png",
},
{
quote:
"Working with Elizabeth was an absolute game-changer. Her technical expertise and commitment to excellence ensured our platform launched smoothly and efficiently.",
name: "James Carter",
title: "CTO of NextGen Tech",
image: "/james.png",
},
{
quote:
"Elizabeth is an exceptional developer with a strong work ethic. She takes the time to ensure every detail is perfect and truly cares about delivering high-quality results.",
name: "Emily Rogers",
title: "Founder of Bright Digital",
image: "/emily.png",
},
{
quote:
"Elizabeth's ability to blend creativity with functionality is unmatched. She delivered a stunning website that perfectly represents our brand.",
name: "David Martinez",
title: "Marketing Director at Visionary Brands",
image: "/david.png",
},
{
quote:
"From start to finish, Elizabeth's dedication and expertise made the entire development process seamless. I highly recommend her for any web development needs.",
name: "Olivia Bennett",
title: "COO of Apex Innovations",
image: "/sarah.png",
},
];

export const companies = [
{
id: 1,
name: "cloudinary",
img: "/cloud.svg",
nameImg: "/cloudName.svg",
},
{
id: 2,
name: "appwrite",
img: "/app.svg",
nameImg: "/appName.svg",
},
{
id: 3,
name: "HOSTINGER",
img: "/host.svg",
nameImg: "/hostName.svg",
},
{
id: 4,
name: "stream",
img: "/s.svg",
nameImg: "/streamName.svg",
},
{
id: 5,
name: "docker.",
img: "/dock.svg",
nameImg: "/dockerName.svg",
},
];

export const workExperience = [
{
id: 1,
title: "Frontend Engineer Intern",
desc: "Assisted in the development of a web-based platform using React.js, enhancing interactivity.",
className: "md:col-span-2",
thumbnail: "/exp1.svg",
},
{
id: 2,
title: "Full Stack Developer",
desc: "Built and optimized full-stack web apps with React, Next.js, Node.js, and MongoDB for seamless performance.",
className: "md:col-span-2", // change to md:col-span-2
thumbnail: "/exp2.svg",
},
{
id: 3,
title: "Freelance App Dev Project",
desc: "Developed and deployed a custom web application tailored to client needs.",
className: "md:col-span-2", // change to md:col-span-2
thumbnail: "/exp3.svg",
},
{
id: 4,
title: "Lead Frontend Developer",
desc: "Developed and maintained user-facing features using modern frontend technologies.",
className: "md:col-span-2",
thumbnail: "/exp4.svg",
},
];

export const socialMedia = [
{
id: 1,
img: "/git.svg",
},
// {
// id: 2,
// img: "/twit.svg",
// },
// {
// id: 3,
// img: "/link.svg",
// },
];
