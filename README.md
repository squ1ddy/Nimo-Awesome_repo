# Nimo-Awesome_repo

<h2><b><u>Usefull Docker Images</u></b></h2>
<ul><p1><b>Vulnerable Apps</b></p1>
<li>https://github.com/citizen-stig/dockermutillidae</li>
<li>https://hub.docker.com/r/opendns/security-ninjas/</li>
<li>https://github.com/remotephone/dvwa-lamp</li>
<li>https://hub.docker.com/r/ismisepaul/securityshepherd/</li>
<li>https://hub.docker.com/r/danmx/docker-owasp-webgoat/</li>
<li>https://github.com/bkimminich/juice-shop</li><br>
<p1 class="lead"><b>Misc Docker</b></p1>
<li>https://hub.docker.com/r/blacktop/cuckoo/    https://github.com/blacktop/docker-cuckoo </li>
<li>Script to check docker security(CIS) - https://hub.docker.com/r/diogomonica/docker-bench-security/ </li>
<li>https://hub.docker.com/r/ahannigan/docker-arachni/</li>
<li>https://hub.docker.com/r/menzo/sn1per-docker/builds/bqez3h7hwfun4odgd2axvn4/</li>
<li> Portainer - Docker manager - http://portainer.io/install.html</li>
  <ul ul style="list-style-type:circle">
  <li> Connect to local host with persistance : <b>docker run -d -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock -v /path/on/host/data:/data portainer/portainer</b></li>
  </ul>
  <li> Kali linux base + web tools installation: https://hub.docker.com/r/kalilinux/kali-linux-docker/
  <ul style="list-style-type:circle">
  <li>apt-get -y install kali-linux-web && apt-get purge</li>
  </ul>
  <li>Malware sample downloader - https://hub.docker.com/r/remnux/maltrieve/ </li>
  <li> Awesome docker repo: https://github.com/veggiemonk/awesome-docker </li>
  <li> OWASP Security Knowledge Framework: https://github.com/blabla1337/skf-flask <br>
  <b>docker run -ti -p 127.0.0.1:443:5443 blabla1337/skf-flask</b></li>
  <li>OWASP security Shepard: https://hub.docker.com/r/ismisepaul/securityshepherd/<br>
  <b>docker run -i -p 80:80 -p 443:443 -t ismisepaul/securityshepherd /bin/bash /usr/bin/mysqld_safe & service tomcat7 start </b><br>
If you don't have authbind installed and configured on your host machine e.g. on Ubuntu you'll need to do the following:
<b><br> 
sudo apt-get install authbind  <br> 
touch /etc/authbind/byport/80  <br> 
touch /etc/authbind/byport/443  <br> 
chmod 550 /etc/authbind/byport/80  <br> 
chmod 550 /etc/authbind/byport/443  <br> 
chown tomcat7 /etc/authbind/byport/80  <br> 
chown tomcat7 /etc/authbind/byport/443</b></li>
</ul>


<p2><b>Misc Usefull Stuff</b></p2>
<ul>
<li>Bypass application whitelisting: http://www.blackhillsinfosec.com/?p=5633</li>
<li>Malcious outlook rules: https://silentbreaksecurity.com/malicious-outlook-rules/ </li>
<li>Great cheatsheets https://highon.coffee/blog/cheat-sheet/ </li>
<li>Headless Browseres https://github.com/dhamaniasad/HeadlessBrowsers </li>
  <li> Linode Linux useful IP commands: https://www.linode.com/docs/networking/linux-static-ip-configuration </li>
  <li>netdata - system for distributed real-time performance and health monitoring: https://github.com/firehol/netdata </li>
</ul>

<h2><strong><u>Threat Hunting && Simulation</u></strong></h2>

  <h3><b>Adversary/Threat Simulation</b></h3>
  <ul>
    <p3>
    <span>
   <li>Uber metta: https://github.com/uber-common/metta </li>
  <li> SANS HELK Part 1: https://isc.sans.edu/forums/diary/Threat+Hunting+Adversary+Emulation+The+HELK+vs+APTSimulator+Part+1/23525/ </li>
  <li> SANS HELK Part 2: <font size="1"> https://isc.sans.edu/forums/diary/Threat+Hunting+Adversary+Emulation+The+HELK+vs+APTSimulator+Part+2/23529/ </font></li>
  <li> CALDERA: https://github.com/mitre/caldera </li>
  <li> Infection Monkey: https://github.com/guardicore/monkey || https://www.guardicore.com/infectionmonkey/</li>
    <li>APTSimulator: https://github.com/NextronSystems/APTSimulator</li>
  <li>atomic-red-team: https://github.com/redcanaryco/atomic-red-team </li>
  <li>Red Team Automation(RTA): https://github.com/endgameinc/RTA </li>
  <li>Network Flight Simulator: https://github.com/alphasoc/flightsim </li>
  <li>Redhunt - Virtual Machine for Adversary Emulation and Threat Hunting: https://github.com/redhuntlabs/RedHunt-OS </li>
  <li> Blue Team Training Kit: https://www.bt3.no/ </li>
    </span>
  </p3>
  </ul>
  <h3><b>Payloads</b></h3>
    <ul>
      <p3>
        <span>
   <li>The Axer - Automatic msfvenom payload generator: https://github.com/ceh-tn/The-Axer </li>
            <li>pwnJS - JS payloads: https://github.com/theori-io/pwnjs </li>
            <li>SpookFlare: https://github.com/hlldz/SpookFlare </li>
          <li>Sharpshooter - payload creation framework for the retrieval and execution of arbitrary CSharp source code: https://www.mdsec.co.uk/2018/03/payload-generation-using-sharpshooter/ || https://github.com/mdsecactivebreach/SharpShooter </li>
          <li>CACTUSTORCH - A JavaScript and VBScript shellcode launcher: https://github.com/mdsecactivebreach/CACTUSTORCH </li>
          <li>DotNetToJScript - A tool to generate a JScript which bootstraps an arbitrary .NET Assembly and class: https://github.com/tyranid/DotNetToJScript </li>
          <li> 
      </span>
     </p3>
          </ul>
            <h3><b>Stealthy Communicatin / Covert Channel</b></h3>
    <ul>
      <p3>
        <span>
          <li>PowerDNS: https://www.mdsec.co.uk/2017/07/powershell-dns-delivery-with-powerdns/ || https://github.com/mdsecactivebreach/PowerDNS </li>
          <li> </li>
          </p3>
        </span>
 
          <ul>
  
  <li>Hunt for C&C channels using bro and rita: https://www.blackhillsinfosec.com/how-to-hunt-command-and-control-channels-using-bro-ids-and-rita/ </li>
  <li>sqrrl hunting email headers: https://sqrrl.com/hunting-email-headers/?utm_source=hs_email&utm_medium=email&utm_content=57387063&_hsenc=p2ANqtz-_PrKGdn4tPttGcvrdPzUazcpHci98ldPOXBJPNG3MssLSS9Ch1xwHq7p6Kq-5NiUlLnTBBasLoM1WT8zUdpLEnKGeFAA&_hsmi=57386424 </li>
  
  
 <li> rockNSM(IDS) installation notes from SANS: https://isc.sans.edu/diary/rss/22832 </li>
<li>DTAG(T-Pot creators) https://github.com/dtag-dev-sec </li>
 
  <li> Endgame Malware BEnchmark for Research (ember): https://github.com/endgameinc/ember </li>
  <li>unfetter: https://github.com/unfetter-analytic/unfetter </li>
  
  <li> DNSCAT2: https://github.com/iagox86/dnscat2 </li>


  <li>DoxuCannon: https://github.com/audibleblink/doxycannon </li>
  <li>Fancy Bear - flatl1ne repo: https://github.com/FlatL1neAPT </li>
  <li>Sensepost Data exfiltration Toolkit(DET): https://github.com/sensepost/DET </li>
  <li>Pyexfil: https://github.com/ytisf/PyExfil </li>
  <li>portspoof: https://github.com/drk1wi/portspoof </li>
  <li> Ultimate AppLocker Bypass List: https://github.com/api0cradle/UltimateAppLockerByPassList/blob/master/README.md</li>
  <li>List of binaries and scripts that can be used for other purposes than they are designed to: https://github.com/api0cradle/LOLBAS </li>
</ul>
<p2><b><u>Online Tools</u></b><p2>
<li>Online packet Analyzer - http://packettotal.com/ </li>
<li>CyberChef: https://gchq.github.io/CyberChef/</li>
<li>Docker Image Analyzer: https://anchore.io/</li>
<li>URL Scanner / Sandbox: https://urlscan.io/</li>
<li>Steve Gibson Shields UP / UPNP Exposure Test: https://www.grc.com/x/ne.dll?rh1dkyd2 </li>
<li>Phish IA: https://app.phish.ai/#/scan_url </li>
<li>Mozilla Observatory: https://observatory.mozilla.org/ </li>
<li>Qualys SSL Labs Server Test: https://www.ssllabs.com/ssltest/ </li>
<li>Qualys SSL Labs Browser Test: https://www.ssllabs.com/ssltest/viewMyClient.html </li>
<li>Explain Shell Commands: https://explainshell.com/ </li>
<li>HTML/CSS/JS interactive Cheatsheet: http://htmlcheatsheet.com/</li>
<li>Misc HTML tools: https://hreftools.com/ </li>

<p2><b>Password Lists</b></p2>
<ul>
<li>https://wiki.skullsecurity.org/index.php?title=Passwords</li>
</ul>

<p2><b><u>Stress Test / Web Traffic Simulation</u></b><p2>
<li>https://loader.io/</li>
<li>https://a.blazemeter.com/app/sign-in</li>
<li>https://artillery.io/</li>
<li> NodeJS Test Cafe: https://devexpress.github.io/testcafe/ </li>

<p2><b>XSS Resources</b></p2>
<ul>
<li>HTML5 - http://html5sec.org/</li>
<li>OWASP - https://www.owasp.org/index.php/XSS_Filter_Evasion_Cheat_Sheet</li>
<li>Reddit - https://www.reddit.com/r/xss/</li>
<li>Js payloads, great tutorials - http://www.xss-payloads.com/index.html</li>
<li>Powerfull web tool for creating event based payloads - http://brutelogic.com.br/webgun/ </li>
<li>Ultimate XSS protection Cheatsheet - https://xenotix.in/The%20Ultimate%20XSS%20Protection%20Cheat%20Sheet%20for%20Developers.pdf </li>
<li>HTML5 attack Vectors - https://dl.packetstormsecurity.net/papers/attack/HTML5AttackVectors_RafayBaloch_UPDATED.pdf </li>
</ul>

| Test command | Somehting here |
| --- | --- |
| 'bla bla bla command' | something here |
| 'short command' | short integer 'True' |
