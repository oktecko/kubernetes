# Kubernetes (K8s)

[![GoPkg Widget]][GoPkg] [![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/569/badge)](https://bestpractices.coreinfrastructure.org/projects/569)

<img src="https://github.com/kubernetes/kubernetes/raw/master/logo/logo.png" width="100">

----

Kubernetes، همچنین به عنوان K8s شناخته می شود، یک سیستم منبع باز برای مدیریت [برنامه های کانتینری] است.
در چندین میزبان مکانیزم های اساسی برای استقرار، نگهداری،
و مقیاس بندی برنامه ها

Kubernetes بر اساس یک دهه و نیم تجربه در Google اجرا شده است
بارهای کاری تولید در مقیاس با استفاده از سیستمی به نام [Borg]،
با بهترین ایده ها و شیوه های جامعه ترکیب شده است.

Kubernetes توسط بنیاد محاسبات Cloud Native ([CNCF]) میزبانی می شود.
اگر شرکت شما می خواهد به شکل گیری تکامل کمک کند
فن آوری هایی که به صورت کانتینری بسته بندی می شوند، به صورت پویا برنامه ریزی شده اند،
و میکروسرویس گرا، پیوستن به CNCF را در نظر بگیرید.
برای جزئیات در مورد اینکه چه کسی درگیر است و Kubernetes چگونه نقش بازی می کند،
CNCF [اطلاعیه] را بخوانید.

----

## برای شروع استفاده از K8s

مستندات ما را در [kubernetes.io] ببینید.

[آموزش تعاملی] ما را امتحان کنید.

یک دوره رایگان در مورد [Microservices Scalable with Kubernetes] بگذرانید.

برای استفاده از کد Kubernetes به عنوان کتابخانه در سایر برنامه‌ها، به [لیست مؤلفه‌های منتشرشده] (https://git.k8s.io/kubernetes/staging/README.md) مراجعه کنید.
استفاده از ماژول "k8s.io/kubernetes" یا بسته های "k8s.io/kubernetes/..." به عنوان کتابخانه پشتیبانی نمی شود.

## برای شروع توسعه K8s

[مخزن انجمن] همه اطلاعات مربوط به آن را میزبانی می کند
ساخت Kubernetes از منبع، نحوه مشارکت کد
و مستندات، با چه کسی در مورد چه چیزی تماس بگیریم و غیره

اگر می خواهید فورا Kubernetes را بسازید دو گزینه وجود دارد:

##### شما یک [محیط برو] کار دارید.

```
mkdir -p $GOPATH/src/k8s.io
سی دی $GOPATH/src/k8s.io
git clone https://github.com/kubernetes/kubernetes
سی دی کوبرنتس
ساختن
```

##### شما یک [محیط Docker] در حال کار دارید.

```
git clone https://github.com/kubernetes/kubernetes
سی دی کوبرنتس
انتشار سریع
```

برای داستان کامل، به [اسناد برنامه‌نویس] بروید.

## پشتیبانی

اگر به پشتیبانی نیاز دارید، با [راهنمای عیب‌یابی] شروع کنید،
و راه خود را از طریق فرآیندی که ما تشریح کردیم، ادامه دهید.

گفت: اگر سوالی دارید، با ما تماس بگیرید
[یک راه یا دیگری] [ارتباط].

[اعلام]: https://cncf.io/news/announcement/2015/07/new-cloud-native-computing-foundation-drive-alignment-among-container
[بورگ]: https://research.google.com/pubs/pub43438.html
[CNCF]: https://www.cncf.io/about
[ارتباطات]: https://git.k8s.io/community/communication
[مخزن انجمن]: https://git.k8s.io/community
[برنامه های کانتینری]: https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/
[اسناد برنامه‌نویس]: https://git.k8s.io/community/contributors/devel#readme
[محیط داکر]: https://docs.docker.com/engine
[محیط برو]: https://golang.org/doc/install
[GoPkg]: https://pkg.go.dev/k8s.io/kubernetes
[ویجت GoPkg]: https://pkg.go.dev/badge/k8s.io/kubernetes.svg
[آموزش تعاملی]: https://kubernetes.io/docs/tutorials/kubernetes-basics
[kubernetes.io]: https://kubernetes.io
[Microservices مقیاس پذیر با Kubernetes]: https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615
[راهنمای عیب یابی]: https://kubernetes.io/docs/tasks/debug/

## جلسات انجمن

[تقویم] (https://www.kubernetes.dev/resources/calendar/) فهرستی از تمام جلسات انجمن Kubernetes را در یک مکان دارد.

## پذیرندگان

وب‌سایت [مطالعات موردی کاربر] (https://kubernetes.io/case-studies/) دارای موارد استفاده واقعی از سازمان‌هایی در سراسر صنایعی است که در حال استقرار/مهاجرت به Kubernetes هستند.

## حکومت

پروژه Kubernetes توسط چارچوبی از اصول، ارزش‌ها، خط‌مشی‌ها و فرآیندها اداره می‌شود تا به جامعه و گروه‌های ما در رسیدن به اهداف مشترکمان کمک کند.

[انجمن Kubernetes] (https://github.com/kubernetes/community/blob/master/governance.md) نقطه شروعی برای یادگیری در مورد نحوه سازماندهی خودمان است.

[مخزن انجمن راهبری Kubernetes] (https://github.com/kubernetes/steering) توسط کمیته راهبری Kubernetes استفاده می‌شود که بر مدیریت پروژه Kubernetes نظارت می‌کند.

## نقشه راه

[مخزن بهبودهای Kubernetes] (https://github.com/kubernetes/enhancements) اطلاعاتی درباره نسخه‌های Kubernetes، و همچنین ردیابی ویژگی‌ها و موارد عقب‌افتاده ارائه می‌دهد.
