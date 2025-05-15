# Exponential-finite-differences
A study of Exponential Finite Differences (EFD) for power sequences (x, x², ..., xⁿ), proving Δⁿ⁻¹ = x(x-1)ⁿ⁻¹. Includes paper, code, and visual proofs.  
## 📜 Licenses  
- **Code**: [MIT License](LICENSE)  
- **Paper/Content**: [CC BY 4.0](LICENSE-CC-BY-4.0.txt)  
## 📜 Abstract  
We prove that for exponentially spaced sequences \((x, x^2, \dots, x^n)\), the \((n-1)\)-th finite difference equals \(x(x-1)^{n-1}\).  

## 🚀 Key Features  
- First closed-form solution for EFDs  
- Applications in cryptography and dynamical systems  

## 📂 Files  
| File | Purpose |  
|------|---------|  
| `paper.pdf` | Full manuscript (LaTeX) |  
| `efd.py` | Python implementation |  

## 🔧 Setup  
```bash
git clone https://github.com/mathsresearcher/exponential-finite-differences.git
python efd.py --test 5  # Verify Δ² for x=5
