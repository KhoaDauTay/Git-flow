# Git flow 
- Step 1: Tạo 1 repo trên gitlab or github, tên : `git-flow-guide`
- Step 2: Trở lại máy tính, tạo 1 folder, ví dụ: `git-flow`
- Step 3: Nhấp chuột phải vào folder, chọn `Open Git Bash here`
- Step 4: Config thông tin của repo 
    ```
    git config --global user.name "Huynh Tan Khoa"
    git config --global user.email "khoa.huynhtan@genefriendway.com"
    ```
- Step 5: Clone dự án từ repo về:
    ```
    git clone git@gitlab.com:khoa-genetica/git-flow-guide.git
    ```
- Step 6: Di chuyển đến thư mục vừa clone
    ```
    cd git-flow-guide
    ```
- Step 6: Tải git-flow về
    ```
    git flow init -d
    ```
    - `-d` là tùy chọn cài mặc định
    - Cài xong, bạn sẽ tự động chuyển từ brach `master` sang `develop`
    ![Kết quả](image/image-1.png)
- Step 7: Bước 1-6 khi bắt đầu dự án, từ step 7 các CLI sẽ được lặp lại đến khi hoàn thành.
    - Tạo feature từ nhánh develop:
    ```
    git flow feature start day-1
    ```
- Step 8: Tạo, thêm, sửa file của bạn. Khi xong, hãy commit nó vào branch `feature/day-1`
    ```
    git commit -m 'Add readme.me'
    ```
- 