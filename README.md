# Genius CDN Assets

A centralized repository for distributing compiled libraries, packaged modules, and web assets via CDN. This project provides easy access to production-ready artifacts for Java, Node.js, and frontend development.

---

## 📦 Available Assets

### ☕ Java (JAR)

#### Genius Utility Library (Spring Boot)
A collection of reusable utilities designed to simplify backend development in Spring Boot applications.

- **Version:** `utils-1.0.4`

#### AES Swing Application
A desktop application built with Java Swing for secure text encryption and decryption using AES-256 (CBC mode).

- **Version:** `aes-swing-1.0.0`

---

### 🌐 Node.js (TGZ)

#### Genius Utility Library (Express.js)
Utility package for Node.js applications using Express, providing helper functions and common backend tools.

- **Package:** `genius-utils-1.0.4`

---

### 🔤 Fonts (WOFF2)

Optimized web fonts for multilingual support.

#### English (EN)
- Apple Chancery  
- Cambria  
- JetBrains Mono  
- Lora  
- Monaco  
- Old Standard TT  
- Oswald  

#### Korean (KR)
- BM Yeon Sung  
- Gowun Dodum  
- Song Myung  

#### Myanmar (MM)
- Burma Thin  
- Burmese Hand Writing  
- Cool Jazz  
- Phetkon  
- Pyidaungsu  
- Yay Chan Zin  
- Z01-Umoe002  

---

## 🚀 Usage

All assets are intended for CDN distribution and can be directly integrated into your applications via public links.

### Example

**Java (Maven dependency via CDN or repository proxy):**
```xml
<dependency>
  <groupId>com.genius</groupId>
  <artifactId>utils</artifactId>
  <version>1.0.4</version>
</dependency>
```

**Node.js (install from TGZ):**
```bash
npm install https://cdn.jsdelivr.net/gh/soehtetpaing/cdn-assets@v1.0.0/tgz/genius-utils-1.0.4.tgz
```

**Fonts (CSS):**
```css
@font-face {
  font-family: 'Burma Thin';
  src: url('https://cdn.jsdelivr.net/gh/soehtetpaing/cdn-assets@v1.0.0/font/mm/BurmaThin.woff2') format('woff2');
}
```

---

## 📌 Notes

- All assets are versioned for stability and backward compatibility.
- Ensure proper caching strategies when using CDN links.
- Fonts are optimized for web performance (WOFF2 format).

---

## 📄 License

Please refer to individual package licenses where applicable.

---

## 🤝 Contribution

Contributions, improvements, and additional asset submissions are welcome. Please follow standard versioning and documentation practices.

---

## 📬 Contact

For issues, feature requests, or support, please open an issue or contact the maintainer.
