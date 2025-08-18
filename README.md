<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mehrdad Mokhtari - Security & IT Infrastructure Professional</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* slate-50 */
            color: #0f172a; /* slate-900 */
        }
        .section-title {
            border-bottom: 2px solid #6366f1; /* indigo-500 */
            padding-bottom: 0.5rem;
        }
        .card {
            background-color: #ffffff;
            border: 1px solid #e2e8f0; /* slate-200 */
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        .tag {
            background-color: #eef2ff; /* indigo-50 */
            color: #4338ca; /* indigo-700 */
            font-weight: 500;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header & Hero Section -->
    <header class="bg-indigo-600 text-white shadow-lg">
        <div class="container mx-auto px-6 py-12 md:py-20">
            <div class="text-center">
                <h1 class="text-4xl md:text-6xl font-bold leading-tight">Mehrdad Mokhtari</h1>
                <p class="mt-4 text-lg md:text-2xl text-indigo-200">Security & IT Infrastructure Professional</p>
            </div>
            <div class="mt-8 flex justify-center space-x-6 text-2xl">
                <a href="https://www.linkedin.com/in/mmokhta/" target="_blank" class="hover:text-indigo-300 transition-colors duration-300"><i class="fab fa-linkedin"></i></a>
                <a href="https://gitlab.com/Mehrdad261" target="_blank" class="hover:text-indigo-300 transition-colors duration-300"><i class="fab fa-gitlab"></i></a>
                <a href="mailto:Mehrdad.mokhtari1370@gmail.com" class="hover:text-indigo-300 transition-colors duration-300"><i class="fas fa-envelope"></i></a>
            </div>
        </div>
    </header>

    <main class="container mx-auto px-6 py-12">

        <!-- About Me Section -->
        <section id="about" class="mb-16">
            <h2 class="text-3xl font-bold mb-6 section-title">About Me</h2>
            <p class="text-lg text-slate-700 leading-relaxed">
                Highly motivated IT & Security Infrastructure Engineer with over 10 years of experience in designing, implementing, and managing complex IT systems and security solutions across on-premises and cloud environments (Azure, AWS). I have a proven ability to lead projects, troubleshoot complex issues, and a strong understanding of ITIL, ISO 27001, and industry best practices.
            </p>
        </section>

        <!-- Experience Section -->
        <section id="experience" class="mb-16">
            <h2 class="text-3xl font-bold mb-8 section-title">Work Experience</h2>
            <div class="space-y-12">
                <!-- OPAL-UK -->
                <div class="card rounded-lg p-6 shadow-md">
                    <div class="flex justify-between items-start">
                        <div>
                            <h3 class="text-xl font-bold text-indigo-600">Senior IT & Security Infrastructure Engineer</h3>
                            <p class="text-md font-semibold text-slate-600">OPAL-UK | St. Albans, UK</p>
                        </div>
                        <p class="text-sm text-slate-500 font-medium">Feb 2024 - Present</p>
                    </div>
                    <ul class="mt-4 list-disc list-inside text-slate-700 space-y-2">
                        <li>Administered AWS cloud environments (IaaS, PaaS, SaaS) and automated deployments using Terraform.</li>
                        <li>Managed security controls including Check Point firewalls, Bitdefender EDR, and MFA.</li>
                        <li>Conducted vulnerability assessments using Intruder and Qualys.</li>
                        <li>Administered Windows/Linux servers, Active Directory, and containerized applications with Docker & Kubernetes.</li>
                        <li>Designed and maintained network infrastructure using Cisco and Dell technologies.</li>
                    </ul>
                </div>
                <!-- UCL -->
                <div class="card rounded-lg p-6 shadow-md">
                     <div class="flex justify-between items-start">
                        <div>
                            <h3 class="text-xl font-bold text-indigo-600">Senior IT Operation</h3>
                            <p class="text-md font-semibold text-slate-600">UCL (University College of London) | London, UK</p>
                        </div>
                        <p class="text-sm text-slate-500 font-medium">Mar 2023 - Apr 2024</p>
                    </div>
                    <ul class="mt-4 list-disc list-inside text-slate-700 space-y-2">
                        <li>Administered and optimized UCL's hybrid cloud environment (Azure) and on-premises data centres.</li>
                        <li>Managed Windows Servers, Active Directory (Azure, On-premises), and Microsoft 365.</li>
                        <li>Ensured system integrity and security by implementing policies compliant with GDPR and ISO 27001.</li>
                        <li>Monitored system performance and streamlined operations through automation.</li>
                    </ul>
                </div>
                <!-- Pars ISP -->
                <div class="card rounded-lg p-6 shadow-md">
                    <div class="flex justify-between items-start">
                        <div>
                           <h3 class="text-xl font-bold text-indigo-600">Senior Security & IT Infrastructure</h3>
                           <p class="text-md font-semibold text-slate-600">Pars ISP | Dubai, UAE</p>
                        </div>
                        <p class="text-sm text-slate-500 font-medium">Feb 2022 - Apr 2023</p>
                    </div>
                    <ul class="mt-4 list-disc list-inside text-slate-700 space-y-2">
                        <li>Managed IT infrastructure including data centres, cloud environments (AWS), and virtualization with VMware.</li>
                        <li>Developed and managed a comprehensive security architecture using firewalls, IDS/IPS, and SIEM (Splunk).</li>
                        <li>Led incident response efforts to identify, contain, and remediate security threats.</li>
                        <li>Conducted regular risk assessments to ensure compliance with industry standards.</li>
                    </ul>
                </div>
                 <!-- Add other experiences similarly -->
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="mb-16">
            <h2 class="text-3xl font-bold mb-6 section-title">Technical Skills</h2>
            <div class="flex flex-wrap gap-3">
                <span class="tag rounded-full px-4 py-2">AWS</span>
                <span class="tag rounded-full px-4 py-2">Azure</span>
                <span class="tag rounded-full px-4 py-2">Terraform</span>
                <span class="tag rounded-full px-4 py-2">Docker</span>
                <span class="tag rounded-full px-4 py-2">Kubernetes</span>
                <span class="tag rounded-full px-4 py-2">Python</span>
                <span class="tag rounded-full px-4 py-2">PowerShell</span>
                <span class="tag rounded-full px-4 py-2">Check Point</span>
                <span class="tag rounded-full px-4 py-2">Cisco</span>
                <span class="tag rounded-full px-4 py-2">VMware</span>
                <span class="tag rounded-full px-4 py-2">Windows Server</span>
                <span class="tag rounded-full px-4 py-2">Linux (RedHat/Ubuntu)</span>
                <span class="tag rounded-full px-4 py-2">Splunk</span>
                <span class="tag rounded-full px-4 py-2">Jenkins</span>
                <span class="tag rounded-full px-4 py-2">Git</span>
            </div>
        </section>

        <!-- Certifications Section -->
        <section id="certifications" class="mb-16">
            <h2 class="text-3xl font-bold mb-6 section-title">Certifications</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="card rounded-lg p-4 flex items-center space-x-4">
                    <i class="fas fa-award text-2xl text-indigo-500"></i>
                    <p class="font-semibold">AWS Solution Architect - Associate</p>
                </div>
                <div class="card rounded-lg p-4 flex items-center space-x-4">
                    <i class="fas fa-award text-2xl text-indigo-500"></i>
                    <p class="font-semibold">Microsoft Certified: Azure Administrator Associate</p>
                </div>
                <div class="card rounded-lg p-4 flex items-center space-x-4">
                    <i class="fas fa-award text-2xl text-indigo-500"></i>
                    <p class="font-semibold">CheckPoint Certified Security Administrator (CCSA)</p>
                </div>
                 <div class="card rounded-lg p-4 flex items-center space-x-4">
                    <i class="fas fa-award text-2xl text-indigo-500"></i>
                    <p class="font-semibold">VMware Certified Professional (VCP-DCV)</p>
                </div>
                <div class="card rounded-lg p-4 flex items-center space-x-4">
                    <i class="fas fa-award text-2xl text-indigo-500"></i>
                    <p class="font-semibold">CCNP Enterprise</p>
                </div>
                 <div class="card rounded-lg p-4 flex items-center space-x-4">
                    <i class="fas fa-award text-2xl text-indigo-500"></i>
                    <p class="font-semibold">ITIL 4 Foundation</p>
                </div>
            </div>
        </section>

        <!-- Education Section -->
        <section id="education">
            <h2 class="text-3xl font-bold mb-6 section-title">Education</h2>
            <div class="card rounded-lg p-6">
                 <h3 class="text-xl font-bold text-indigo-600">Bachelor of Science in Software Engineering</h3>
                 <p class="text-md font-semibold text-slate-600">Isfahan University | Isfahan, Iran</p>
                 <p class="text-sm text-slate-500 mt-1">Graduated: July 2011</p>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-slate-800 text-slate-400 mt-16">
        <div class="container mx-auto px-6 py-8 text-center">
            <p>&copy; 2024 Mehrdad Mokhtari. All Rights Reserved.</p>
            <p class="mt-2 text-sm">Built with HTML and Tailwind CSS.</p>
        </div>
    </footer>

</body>
</html>
