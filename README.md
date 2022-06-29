<p align="center">
   <a href="https://github.com/nitzan-treg/community_projects/">
    <img alt="Website" src="https://img.shields.io/website?label=main%20project&up_message=Community%20Projects&url=https%3A%2F%2Fgithub.com%2Fnitzan-treg%2Fcommunity_projects">
  </a>
  <a href="https://github.com/nitzan-treg/community_projects/">
    <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/nitzan-treg/2021_10_09_dvdp_II">
  </a>
  <a href="https://www.nitzan-tregerman.com/">
    <img alt="Website" src="https://img.shields.io/website?up_message=nitzan-tregerman.com&url=https%3A%2F%2Fwww.nitzan-tregerman.com%2F">
  </a>
  <img alt="GitHub" src="https://img.shields.io/github/license/nitzan-treg/2021_10_09_dvdp_II">
</p>

# Davidope II
This project is very much inspired by davidope's art https://www.instagram.com/dvdp/

Its an attempt to create a satisfying looping animation in the black & white style of davidope
I used a falloff and a rotation matrix to control the animation
```c++
//get data
int prims[] = pointprims(0,i@ptnum);
float falloff = f@falloff;
matrix xform = ident();

//rotate matix
vector rnd_axis = normalize(rand(prims[0]+111));
v@rnd_axis = rnd_axis;
float rotate_amp = radians(chf('rotate_amount')*falloff);

rotate(xform,rotate_amp,rnd_axis);

v@P*=xform;
```
<img alt = "gif" src="Images/2021_10_09_dvdp_II.gif">

<img src="Images/Node Tree.png">


<p align="center">
   I share my personal projects for free with everyone.
</p> 

<p align="center">
   You are welcome to explore all of them
   <a href="https://github.com/nitzan-treg/community_projects/">
      here
   </a>
</p> 
   
