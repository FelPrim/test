Уравнение второго порядка от 2 переменных 

$$F(x,y,u,u_{x},u_{y},u_{xx},u_{xy},u_{yy})=0$$
	

$$u_{x}=\frac{\partial}{\partial x} u$$

Уравнение, линейное относительно старих производных: 

$$a_{11}u_{xx}+2a_{12}u_{xy}+a_{22}u_{yy}+\overline{F}(x,y,u,u_{x},u_{y})=0$$


$$\begin{gather} a_{ij}=a_{ij}(x,y) \to \text{Линейное} 
\\
 a_{ij}=a_{ij}(x,y,u,u_{x},u_{y})\to \text{Квазилинейное} \end{gather}$$

Линейное уравнение второго порядка: 

$$a_{11}u_{xx}+2a_{12}u_{xy}+a_{22}u_{yy}+b_{1}u_{x}+b_{2}u_{y}+cu=f$$


$$\begin{gather} \begin{cases} x=x(\xi,\eta) \\ y=y(\xi,\eta) \end{cases}, \ \begin{cases} \xi=\xi(x,y) \\ \eta=\eta(x,y) \end{cases} \\ u(x,y) \to \tilde{u}(\xi,\eta)=u(x(\xi,\eta),y(\xi,\eta)) \\ \text{Дальше мы будем писать $u$ вместо $\tilde{u}$, хоть это и не верно с формальной точки зрения} \\ u_{x}=u_{\xi}\xi_{x}+u_{\eta}\eta_{x}\\ u_{y}=u_{\xi}\xi_{y}+u_{\eta}\eta_{y} \\ u_{xx}=u_{\xi \xi}\xi_{x}^2+2u_{\xi \eta}\xi_{x}\eta_{x}+u_{\eta \eta}\eta_{x}^2+u_{\xi}\xi_{xx}+u_{\eta}\eta_{xx} \\ u_{yy}=u_{\xi \xi}\xi_{y}^2+2u_{\xi \eta}\xi_{y}\eta_{y}+u_{\eta \eta}\eta_{y}^2+u_{\xi}\xi_{yy}+u_{\eta}\eta_{yy} \\ u_{xy}=u_{\xi \xi}\xi_{x}\xi_{y}+u_{\xi \eta}(\xi_{x}\eta_{y}+\xi_{y}\eta_{x})+u_{\eta \eta}\eta_{x}\eta_{y}+u_{\xi}\xi_{xy}+u_{\eta}\eta_{xy} \end{gather}$$