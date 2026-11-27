---
layout: default
---

{% assign cv_pdf = site.static_files | where: 'path', '/assets/cv.pdf' | first %}
{% assign cv_link = '#cv' %}
{% if cv_pdf %}{% assign cv_link = cv_pdf.path | relative_url %}{% endif %}

[Giới thiệu](#gioi-thieu) [Kinh nghiệm](#kinh-nghiem) [Dự án](#du-an) [Kỹ năng](#ky-nang) [Liên hệ](#lien-he) [CV]({{ cv_link }})
{: .profile-nav }

![Ảnh đại diện trên GitHub](https://github.com/anhquoc291005.png?size=320)
{: .profile-avatar }

**Hồ sơ cá nhân**
{: .profile-label }

# Anh Quoc
{: .profile-name }

CV trực tuyến · Kinh nghiệm, học vấn và dự án
{: .profile-role }

[Xem GitHub](https://github.com/anhquoc291005) [{% if cv_pdf %}Xem CV PDF{% else %}Thông tin CV{% endif %}]({{ cv_link }})
{: .profile-links }

## Giới thiệu {#gioi-thieu}

Hồ sơ đang được cập nhật.
{: .pending }

## Kinh nghiệm và học vấn {#kinh-nghiem}

Thời gian làm việc
: **Kinh nghiệm**
  Thông tin về vị trí, tổ chức và đóng góp đang được cập nhật.

Thời gian học
: **Học vấn**
  Thông tin về trường và chuyên ngành đang được cập nhật.
{: .experience-list }

## Dự án {#du-an}

Bạn có thể xem các dự án công khai [trên GitHub](https://github.com/anhquoc291005?tab=repositories).

## Kỹ năng {#ky-nang}

Thông tin kỹ năng sẽ được bổ sung.
{: .pending }

## Liên hệ {#lien-he}

[GitHub · @anhquoc291005](https://github.com/anhquoc291005)

## CV {#cv}

{% if cv_pdf %}
[Xem CV bản PDF]({{ cv_link }})
{% else %}
Bản CV PDF sẽ được bổ sung.
{: .pending }
{% endif %}
