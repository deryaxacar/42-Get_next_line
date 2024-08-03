<!-- Proje Başlığı -->
<h1 align="center">42 - Get_next_line 📄</h1>

<!-- Proje Açıklaması -->
<p align="center">
Bu proje, standart giriş işleviyle bir dosyadan satır okumayı sağlar. get_next_line işlevi, bir dosyadan karakter okumak için kullanılırken, aynı zamanda birden çok dosyayı eş zamanlı olarak işleyebilir.
</p>

<!-- Proje Logosu veya Görseli -->
<p align="center">
  <a target="blank"><img src="https://i.hizliresim.com/pjpsbji.png" height="150" width="150" /></a>
</p>

## Projenin Amacı 🎯

Bu proje, dosya işleme, bellek yönetimi ve iş parçacığı programlaması konularında deneyim kazanmamıza yardımcı olur. Ayrıca, bu projede statik bir bellek alanının nasıl etkin bir şekilde kullanılacağını, dosyalarla etkileşimde bulunmayı ve giriş/çıkış işlemlerini yönetmeyi öğreniriz.

## Kullanım Senaryoları 📋

get_next_line işlevi, bir dosyadan satır okuma işlemi yapar ve bu işlem bir veya daha fazla kez çağrılabilir. Kullanım senaryoları şunları içerebilir:

- Bir dosyadan satır satır okuma: `get_next_line(fd, &line);`
- Birden çok dosyadan aynı anda okuma yapma: `get_next_line(fd1, &line1); get_next_line(fd2, &line2);`

## Proje İçeriği 📂

Proje, get_next_line işlevinin yanı sıra yardımcı işlevleri ve yapılarını içerir. Bu içerik şunları içerebilir:

- **get_next_line.c**: Ana get_next_line işlevinin tanımlarını içerir.
- **get_next_line.h**: Proje başlık dosyası, prototipleri ve yapı tanımlarını içerir.
- **get_next_line_bonus.c**: Bonus kısmı için ekstra işlevlerin tanımlarını içerir.
- **get_next_line_bonus.h**: Bonus kısmı için başlık dosyası, prototipleri ve yapı tanımlarını içerir.
- **get_next_line_utils.c**: Yardımcı işlevlerin tanımlarını içerir.
- **get_next_line_utils_bonus.c**: Bonus kısmı için yardımcı işlevlerin tanımlarını içerir
