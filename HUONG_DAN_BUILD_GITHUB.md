Tạo một GitHub repository trống cho bản TrollVNC 3.3-1011.
Chạy `git remote add origin <URL>` để gắn URL repository của bạn.
Chạy `git push -u origin main` để đẩy nhánh main.
GitHub Actions sẽ chạy workflow Build TrollVNC cho default, rootless và roothide.
Tải artifact packages-default/rootless/roothide; mỗi gói có `.deb` gốc và bản sao TrollVNC-iosview_3.3-1011_{rootful|rootless|roothide}.deb.
