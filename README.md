**Implement analytics solution of Kovasznay flow**
This flow model could be using for first research in flow models (because it is 2D, steady and you can explore viscosity dependence (Rereynolds number) directly or for compare with another type soltuion for partial differential equation

$$
 \lambda=\frac{1}{2}\left(Re{-\sqrt{{Re}^2{+16}{Re}^2}}\right)
$$

Or if you want friction dependence (but only if Re<2300): 

$$
\lambda=\frac{64}{Re}
$$

$$
v_x=1-e^{\lambda x}cos{\left(2\pi Y\right)}
$$

$$
v_y=\frac{\lambda}{2\pi}e^{\lambda x}\sin{\left(2\pi x\right)}
$$

$$
p=\frac{1}{2}\left(1-e^{2\lambda x}\right)
$$

**You see this speed enhance in centre of Y (x=0), because Kovasznay flows around the arrows creating periodic disturbances on both sides of the lattice**

![image](https://github.com/user-attachments/assets/eafc44cf-3ca4-45ca-b50d-5961a5e2c611)

**This pictures demonstrate how flow change direction after arrows**

![image](https://github.com/user-attachments/assets/a7e89fbd-df63-4df0-8d44-cef5835271ea)


![image](https://github.com/user-attachments/assets/cfa37c68-350d-4e64-8e89-f7823512c2ad)
