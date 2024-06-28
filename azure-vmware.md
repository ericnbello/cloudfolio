<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Hybrid Azure AD Home Lab</h1>
		</header>

<!-- Content -->
<h2 id="content">Overview</h2>
    <p>This project outlines the setup and configuration of a hybrid Active Directory (AD) environment that integrates on-premises infrastructure with Azure. The lab includes a VMWare virtual home lab running a Windows Server 2019 domain controller and Windows 10 clients, synchronized with Azure for hybrid identity management and seamless single sign-on (SSO).</p>

<h3>Project Goals</h3>
    <ul>
        <li><strong>Setup VMWare Virtual Home Lab</strong>
            <ul>
                <li>Configure VMWare Workstation/Fusion environment.</li>
                <li>Deploy Windows Server 2019 as the domain controller and Windows 10 as client machines.</li>
            </ul>
        </li>
        <li><strong>Windows Server 2019 Configuration</strong>
            <ul>
                <li>Define domain settings, server name, and TCP/IP settings.</li>
                <li>Enable and configure remote desktop for management purposes.</li>
            </ul>
        </li>
        <li><strong>Active Directory Configuration</strong>
            <ul>
                <li>Modify default Active Directory templates to meet specific lab requirements.</li>
                <li>Create and link Group Policy Objects (GPOs) to manage user and computer settings within the domain.</li>
            </ul>
        </li>
        <li><strong>Azure Integration</strong>
            <ul>
                <li>Install and configure Azure AD Connect to synchronize on-premises AD with Azure AD.</li>
                <li>Enable hybrid Azure AD join for seamless SSO.</li>
                <li>Configure password hash synchronization to ensure secure user authentication across environments.</li>
            </ul>
        </li>
    </ul>

<h3>Lab Setup</h3>
    <ol>
        <li><strong>VMWare Virtual Home Lab</strong>
            <ul>
                <li><strong>Environment:</strong> VMWare Workstation/Fusion</li>
                <li><strong>Domain Controller:</strong> Windows Server 2019</li>
                <li><strong>Clients:</strong> Windows 10</li>
            </ul>
        </li>
    </ol>

<h3>Detailed Steps</h3>
    <ol>
        <li><strong>Assembling the VMWare Virtual Home Lab</strong>
            <ol type="a">
                <li>Install VMWare Workstation/Fusion on the host machine.</li>
                <li>Create virtual machines for Windows Server 2019 and Windows 10 clients.</li>
                <li>Install respective operating systems on each VM.</li>
            </ol>
        </li>
        <li><strong>Configuring Windows Server 2019</strong>
            <ol type="a">
                <li><strong>Define Domain Settings:</strong>
                    <ul>
                        <li>Use Server Manager to add the AD DS role.</li>
                        <li>Promote the server to a domain controller with the desired domain name.</li>
                    </ul>
                </li>
                <li><strong>Configure TCP/IP Settings:</strong>
                    <ul>
                        <li>Assign a static IP and configure DNS settings.</li>
                    </ul>
                </li>
                <li><strong>Enable Remote Desktop:</strong>
                    <ul>
                        <li>Access System Properties to activate remote desktop and adjust firewall settings.</li>
                    </ul>
                </li>
            </ol>
        </li>
        <li><strong>Modifying Active Directory and GPOs</strong>
            <ol type="a">
                <li><strong>Modify AD Templates:</strong>
                    <ul>
                        <li>Utilize Active Directory Users and Computers to customize templates.</li>
                    </ul>
                </li>
                <li><strong>Create and Link GPOs:</strong>
                    <ul>
                        <li>Access Group Policy Management to establish and associate GPOs with applicable OUs.</li>
                    </ul>
                </li>
            </ol>
        </li>
        <li><strong>Implementing Azure AD Connect Sync</strong>
            <ol type="a">
                <li><strong>Install Azure AD Connect:</strong>
                    <ul>
                        <li>Download and install Azure AD Connect software on the domain controller.</li>
                        <li>Configure synchronization parameters for seamless integration between on-premises AD and Azure AD.</li>
                    </ul>
                </li>
                <li><strong>Enable Hybrid Azure AD Join:</strong>
                    <ul>
                        <li>Adjust device settings within Azure AD Connect to enable hybrid Azure AD join functionality.</li>
                    </ul>
                </li>
                <li><strong>Configure Password Hash Synchronization:</strong>
                    <ul>
                        <li>Incorporate password hash synchronization during Azure AD Connect setup to bolster authentication security.</li>
                    </ul>
                </li>
            </ol>
        </li>
    </ol>

<h3>Conclusion</h3>
    <p>This project serves as a comprehensive guide for integrating on-premises Active Directory with Azure, offering a robust solution for hybrid identity management. By following the steps outlined, users can achieve seamless SSO and secure authentication across their hybrid environments, showcasing practical expertise in AD, Azure integration, and hybrid identity management.</p>

<!-- <h4>Fit</h4> -->
<div class="image fit">
<img src="{% link assets/images/VMWare-azure.png %}" alt="" />
</div>

</div>
</section>