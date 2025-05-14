<div style="position: relative; width: 100%; height: 150px; overflow: hidden;">
  <canvas id="starsCanvas" style="position: absolute; top: 0; left: 0; z-index: 0;"></canvas>
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; z-index: 1; pointer-events: none;">
    <h1 align="center">
      <img src="https://readme-typing-svg.demolab.com ?font=Fira+Code&weight=600&size=26&duration=2000&pause=500&color=5C9DF1&center=true&vCenter=true&width=500&lines=Danilchenko+Paul;Professional+C%2FC%2B%2B+Developer;System+Programming" alt="Typing Text" />
    </h1>
  </div>

  <script>
    const canvas = document.getElementById('starsCanvas');
    const ctx = canvas.getContext('2d');
    let w = canvas.width = window.innerWidth;
    let h = canvas.height = 150;

    const numStars = 100;
    const stars = [];

    for (let i = 0; i < numStars; i++) {
      stars.push({
        x: Math.random() * w,
        y: Math.random() * h,
        r: Math.random() * 1.5,
        dx: (Math.random() - 0.5) * 0.5,
        dy: (Math.random() - 0.5) * 0.5
      });
    }

    function draw() {
      ctx.clearRect(0, 0, w, h);
      ctx.fillStyle = 'rgba(10, 10, 30, 0.8)';
      ctx.fillRect(0, 0, w, h);

      for (let star of stars) {
        ctx.beginPath();
        ctx.arc(star.x, star.y, star.r, 0, Math.PI * 2);
        ctx.fillStyle = '#ffffff';
        ctx.fill();

        star.x += star.dx;
        star.y += star.dy;

        if (star.x < 0 || star.x > w) star.dx *= -1;
        if (star.y < 0 || star.y > h) star.dy *= -1;
      }

      requestAnimationFrame(draw);
    }

    draw();
  </script>
</div>

<div align="center">

[![Telegram](https://img.shields.io/badge/- @Paul_von_Daniels-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=2CA5E0)](https://t.me/Paul_von_Daniels )
[![Email](https://img.shields.io/badge/-www.facemash @gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=D14836)](mailto:www.facemash@gmail.com)
[![LeetCode](https://img.shields.io/badge/-LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=FFA116 )](https://leetcode.com/u/paulvondaniels/ )
[![Stack Overflow](https://img.shields.io/badge/-Stack_Overflow-FE7A16?style=for-the-badge&logo=stackoverflow&logoColor=white&labelColor=FE7A16 )](https://ru.stackoverflow.com/users/713493/lorraineboza-wilelkwile )

</div>

<div align="center">
  <img src="https://github.com/DanilchenkoPaul/DanilchenkoPaul/blob/main/assets/divider.gif?raw=true " width="800" height="3" alt="divider">
</div>

## 🛠️ Core Tech Stack

<div align="center">
  
| **Languages** | **Tools & Frameworks** | **Environments** |
|---------------|------------------------|------------------|
| ![C](https://img.shields.io/badge/-C-00599C?style=flat-square&logo=c&logoColor=white ) | ![CMake](https://img.shields.io/badge/-CMake-064F8C?style=flat-square&logo=cmake&logoColor=white ) | ![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black ) |
| ![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white ) | ![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white ) | ![GDB](https://img.shields.io/badge/-GDB-4B8BBE?style=flat-square&logo=gnu&logoColor=white ) |

</div>

### 🎯 Areas of Interest
- Low-latency systems
- Memory management & optimization
- Multithreading & concurrency
- Embedded systems development

---

## 📚 Currently Learning
- Advanced C++20 features
- Linux kernel development
- Performance optimization techniques
- Embedded systems architecture

---

## 💼 Career Focus

Seeking opportunities to:
- Develop high-performance systems
- Optimize critical code paths
- Contribute to meaningful open-source projects
- Work with cutting-edge hardware technologies

---

<blockquote style="text-align:center; font-style: italic; color: #aaa; border-left: 3px solid #555; padding-left: 1em;">
  "If you want to know what God thinks about money, look at who he gave it to."
</blockquote>

---

<div align="center">
  <img src="https://github.com/s-shemmee/s-shemmee/blob/output/github-contribution-grid-snake-dark.svg " alt="Snake animation" />
</div>

<br />

<div align="center" style="font-family: monospace; font-size: 0.9em; color: #555;">
  <!-- Keyboard Signature -->
  <p>Compiled in GCC 13.2 • Built on Arch Linux • Optimized by hand</p>
  <p>Generated using pure C++ logic and cosmic energy.</p>
</div>
