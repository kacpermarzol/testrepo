# Sceny dynamiczne

## Autor
* Kacper Marzol
  * [github](github.com/kacpermarzol)
  * discord @Kacper

Tematem dzisiejszej prezentacji są sceny dynamiczne.
Przeanalizujemy jak wyglądają datasety dla takiego zagadnienia i omówimy 3 modele, które skupiają się na obiektach dynamicznych. Będą to:
* D-NeRF
* 4D Gaussian Splatting
* MonST3R

Prezentacja oraz 4 zadania pozwalające lepiej zrozumieć przekazywane treści znajdują się w notatniku dynamic.ipynb. Ponadto, repozytorium składa się z:
* folderu pics (do celów prezentacji)
* folderu helpers - gdzie znajdziemy kod potrzebny do wizualizacji D-NeRFa
* pliku requirements.txt dla stworzenia środowiska

ponadto powinniśmy stworzyć folder logs, gdzie umieścimy folder 'lego' pobrany [stąd](https://www.dropbox.com/scl/fi/5oyd2uop62yw1ttlw1x5v/logs.zip?rlkey=5ko5sf3njkjv3vssonk1jmruy&e=1&dl=0), jest to checkpoint dla D-NeRF (nie jest to konieczne do wykonania zadań)

### Tworzenie środowiska
W pliku requirements.txt znajduje się lista modułów niezbędna do stworzenia środowiska i odpalenia notebooka.
Można to zrobić np. za pomocą condy:

```angular2html
conda create --name dynamic python=3.9 anaconda
conda activate dynamic
pip install -r requirements.txt
```

### Źródła:
* [D-NeRF: Neural Radiance Fields for Dynamic Scenes
](https://openaccess.thecvf.com/content/CVPR2021/papers/Pumarola_D-NeRF_Neural_Radiance_Fields_for_Dynamic_Scenes_CVPR_2021_paper.pdf)
* [https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_low.pdf](3D Gaussian Splatting for Real-Time Radiance Field Rendering
)
* [4D Gaussian Splatting for Real-Time Dynamic Scene Rendering](https://arxiv.org/pdf/2310.08528)
* [DUSt3R: Geometric 3D Vision Made Easy](https://arxiv.org/pdf/2312.14132)
* [MonST3R: A Simple Approach for Estimating Geometry in the Presence of Motion](https://monst3r-project.github.io/files/monst3r_paper.pdf)


## Dla zainteresowanych:
* [Instant-NVR: Instant Neural Volumetric Rendering for Human-object Interactions from Monocular RGBD Stream
](https://arxiv.org/pdf/2304.03184)