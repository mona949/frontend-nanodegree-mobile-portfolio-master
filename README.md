# frontend-nanodegree-mobile-portfolio
P4 Udacity Front-end Nanodegree Program
### Optimizations
- Brought some of the small scripts and styles inside the `head` element to reduce the CRP.
- Mark the print css link as media type `print` to reduce the CRP overhead for normal displays
- Reduce the size of the pizza image by scaling it down to the actual display dimensions
- Change the image src to `b64` to reduce CRP (I understand this might actually increase the CPU usage compared to jpeg/png and also lowers performance for cached websites, but was just trying to decrease the CRP as much as possible)