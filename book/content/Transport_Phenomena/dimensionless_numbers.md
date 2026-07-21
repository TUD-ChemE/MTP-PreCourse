# Dimensionless Numbers

In transport phenomena, where we deal with the transport of conserved physical quantities such as mass, energy and momentum, several dimensionless numbers play pivotal roles in analyzing the problem being discussed. Below, an overview of these numbers is provided.

```{tip} 
Do not try to remember the dimensionless numbers by heart! Please note the basic physical meaning of the numerator and the denominator terms for each of them, and check the dimensions. In the end, all the numbers must be dimensionless! 

The units are deliberately left out of this document, so please recall or look them up!
```

## Dimensionless numbers similar between Mass and Energy transport
### Peclet Number
Peclet number compares \textcolor{blue}{convective} and \textcolor{blue}{diffusive} transport. For both mass and energy transport, this corresponding number comparing convection and diffusion is called the Peclet Number (Pe). 

Peclet number for mass transport, denoted by $\textrm{Pe_{M}}$ is given by:  

$$
\textrm{Pe$_{M}$}=\frac{vL}{\mathcal{D}} \nonumber
$$

where, $v$=characteristic velocity of the system, $L$=characteristic length of the system, and $\mathcal{D}$ is the mass diffusion constant of the system.

Peclet number for energy transport, denoted by $Pe$ is given by:  

$$
\textrm{Pe}=\frac{vL}{\alpha} \nonumber
$$

where, $v$=characteristic velocity of the system, $L$=characteristic length of the system, and $\alpha$ is the thermal diffusivity of the system, which can be expressed as $\alpha=\frac{\lambda}{\rho c_P}$, where, $\lambda$ is the thermal conductivity, $\rho$ is the density and $c_P$ is the specific heat capacity (at constant pressure) of the system.

### Sherwood Number & Nusselt Number
Sherwood number and Nusselt number compare the same things both for mass and energy transport: the \textcolor{blue}{total} amount of transport and the \textcolor{blue}{diffusive} part of that transport.

Sherwood number compares total mass transport with diffusive mass transport, denoted by:  

$$
\textrm{Sh}=\frac{k_m L}{\mathcal{D}} \nonumber
$$

where, $k_m$=overall mass transfer coefficient of the system, $L$=characteristic length of the system, and $\mathcal{D}$ is the mass diffusion constant of the system.

Nusselt number, denoted by $Nu$, compares the total heat transport in a system with the diffusive (conductive) heat transport in that system, and is given by:  

$$
\textrm{Nu}=\frac{hL}{\lambda} \nonumber
$$

where, $h$=overall heat transfer coefficient of the system, $L$=characteristic length of the system, and $\lambda$ is the thermal conductivity of the system.

### Schmidt Number & Prandtl number
Schmidt Number and Prandtl Number compare the same things for mass and energy transport, respectively: the \textcolor{blue}{momentum diffusivity} and the \textcolor{blue}{mass/thermal diffusivity}.

Schmidt Number compares momentum diffusivity and mass diffusivity, denoted by:  

$$
\textrm{Sc}=\frac{\nu}{\mathcal{D}}=\frac{\mu}{\rho \mathcal{D}} \nonumber
$$

where, $\nu$=the kinematic viscosity of the system, and $\mathcal{D}$ is the mass diffusion constant of the system. The kinematic viscosity $\nu$ can be expressed as $\nu=\frac{\mu}{\rho}$, where, $\mu$ is the dynamic viscosity, and $\rho$ is the density of the system.

Prandtl number, denoted by $Pr$, compares momentum diffusivity and thermal diffusivity, and is given by:  

$$
\textrm{Pr}=\frac{\nu}{\alpha}=\frac{\mu c_P} {\lambda} \nonumber
$$

where, $\nu$=the kinematic viscosity of the system, which can be expressed as $\nu=\frac{\mu}{\rho}$, where, $\mu$ is the dynamic viscosity, and $\rho$ is the density of the system; and, $\alpha$ is the thermal diffusivity of the system, which can be expressed as $\alpha=\frac{\lambda}{\rho c_P}$, where, $\lambda$ is the thermal conductivity, $\rho$ is the density and $c_P$ is the specific heat capacity (at constant pressure) of the system.

### Fourier Number
Fourier number compares \textcolor{blue}{the actual time of transport} and \textcolor{blue}{the characteristic time of diffusive transport}. For both mass and energy transport, this corresponding number is called the Fourier Number (Fo). 

Fourier number for mass transport, denoted by $\textrm{Fo_{M}}$ is given by: 

$$
\textrm{Fo$_{M}$}=\frac{t}{t_c}=\frac{t}{L^2/\mathcal{D}}=\frac{\mathcal{D} t}{L^2} \nonumber
$$

where, $t$=duration of mass transport, $t_c$=characteristic time for diffusive transport, which is rewritten as $L^2/\mathcal{D}$ where, $L$=characteristic length of the system, and $\mathcal{D}$ is the mass diffusion constant of the system.

Fourier number for energy transport, denoted by $Fo$ is given by:  

$$
\textrm{Fo}=\frac{t}{t_c}=\frac{t}{L^2/\alpha}=\frac{\alpha t}{L^2} \nonumber
$$

where, $t$=duration of energy transport, $t_c$=characteristic time for diffusive heat transport, which is rewritten as $L^2/\alpha$ where, $L$=characteristic length of the system, and $\alpha$ is the heat diffusivity of the system.

## Dimensionless number unique to momentum transport
### Reynolds Number
Reynolds number compares inertial forces with viscous forces and is given by: 

$$
\textrm{Re}=\frac{\rho v L}{\mu}=\frac{v L}{\mu/\rho}=\frac{v L}{\nu}\nonumber
$$

where, $\rho$=the density, $v$=the characteristic velocity, $L$=the characteristic length, $\mu$ is the dynamic viscosity, and $\nu$=the kinematic viscosity of the system.
