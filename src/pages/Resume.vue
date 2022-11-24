<template>
  <Layout>
    <h1>Robert Stelling resume</h1>
    <p>Software developer with 40 years of experience, initially real-time embedded
    and now mostly Windows desktop developent.</p>
    <p><b>SRI INTERNATIONAL</b> January 2011 to Present / <b>SARNOFF</b>, Princeton, May 2005 – December 2010</p>
    <p>
    
    <p><a href="https://www.sri.com/national-security/">Integrated Systems Division</a>:</p>
<p>For Open Water Impact Location, developed a C#/WPF GUI Command & Control and Post Mission Impact Analysis program for 
scoring impact location of missiles targeted to hit targets (e.g., surplus boats) on ocean test ranges. Program interfaces 
with HTTP API on service running on 
<a href="https://www.liquid-robotics.com/wave-glider/how-it-works/"> Liquid Robotics Wave Gliders</a> carrying cameras and inertial navigation devices. 
During mission controls camera power, recording and streaming and Pan/Tilt/Zoom sensor control. Post mission provides 
annotation of trajectory, impact location and uses OpenCV to generate composite images with from multiple frames 
containing missile images. Extensive use of WPF User Controls and Model View View Model framework. Mission data stored 
in SQL Server 2019. Starting to mentor others to join the effort.
 </p>
 <p>
    <p><a href="https://www.sri.com/computer-vision/"> Center For Vision Technologies</a> group:</p>
 
 <p>For <a href="https://www.globalsecurity.org/intell/systems/night-eagle.htm">Army NightEagle</a>, developed C#/WPF GUI to process manned-aircraft video and metadata for a Counter Improved Explosive Devices program. Maintain C#/C++/WinForms GUI for review of day to day changes automatically and manually detected in the video frames. Additional technologies used include WCF, Google Earth/KML generation, terrain display with CesiumJS, JavaScript, jQuery, MongoDB, MySQL, Sqlite, OpenCV, GDAL, OxyPlot, NSIS and InstallShield installers, Jenkins, Jira.
</p>
<p>For <a href="http://lidar.io/projects/grid/"> Geospatial Repository and Data Management System</a>: Created C++
 <a href="https://github.com/PDAL/PDAL">PDAL</a> Point Cloud 
filter integrating “bare earth extraction” for LIDAR capability into PDAL. Developed Bash/AWK scripts for automated testing. Created Docker and Conda, gitlab-continuous integration and Jenkins configurations for deployment. Analyzed memory / Created Python script to estimate memory 
or tile size requirements from the other, from data plotted by the automated scripts mentioned above.
</p>
<p>For <a href="https://www.iarpa.gov/research-programs/finder">IARPA FINDER </a> image geolocation program, developed Java REST API using Spring BOOT with ThymeLeaf web interface. Developed with Virtual Box Linus installation and integrated on Amazon AWS. 
</p>
<p>For <a href="https://www.iarpa.gov/research-programs/aladdin-video">IARPA Aladdin</a>, machine-learning video/audio processing program, updated KnockoutJS front-end and NodeJS backend. Additional technologies include REDIS, Zookeeper, MariaDB/MySQL
 </p>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Resume'
  }
}
</script>
