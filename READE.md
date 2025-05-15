# GitHub Actions Lab

Một repo thực hành GitHub Actions với nhiều môi trường CI:

## 📁 Bao gồm:

- `node.yml`: Dự án Node.js với setup node
- `dotnet.yml`: Build .NET trên Windows
- `python.yml`: Python với pytest
- `mixed-shell.yml`: Dùng bash và PowerShell trong 1 workflow
- `install-extra.yml`: Cài thêm phần mềm chưa có sẵn trên runner

## 💡 Mục tiêu:

- Biết cách chọn OS phù hợp (`runs-on`)
- Pin version SDK cụ thể để tránh lỗi
- Sử dụng shell đúng cách theo OS
- Cài thêm công cụ tùy chọn một cách an toàn
- Áp dụng actions phổ biến: `checkout`, `setup-*`, `run`

Bạn nên clone repo và thử từng file để hiểu rõ hành vi của runner.