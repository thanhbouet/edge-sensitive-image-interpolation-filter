# edge-sensitive-image-interpolation-filter
  Bộ lọc nội suy ảnh dựa trên bài nghiên cứu của Sergio Carrato, Giovanni Ramponi, and Stefano Marsi (Đại học Trieste, Italia), theo đó sử dụng một thuật toán mới nhằm khắc phục nhược điểm của các phương pháp nội suy nổi tiếng (Linear, Medium, Average).
  Chương trình python triển khai một bộ lọc nội suy ảnh bằng OpenCV, đưa ảnh về một mảng 3 chiều, trong đó mỗi điểm ảnh được biểu diễn bằng một mảng 3 phần tử (R,G,B). Từ đó xử lý các điểm ảnh bằng ma trận được chuyển đổi từ ảnh gốc. Từ ảnh NxN, sau khi nội suy ta được một ảnh 2Nx2N và vẫn giữ được độ nét cần có.
  Code triển khai và bài nghiên cứu được đính kèm trong project.
