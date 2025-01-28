# 💻 **Ransomware na Prática com Python**
Este repositório apresenta um projeto educacional sobre a criação de um ransomware utilizando Python. **O objetivo é exclusivamente educacional**, buscando ensinar conceitos de cibersegurança, análise de malware e boas práticas para proteger sistemas contra ataques.

⚠️ **ATENÇÃO**: Este projeto é apenas para fins de estudo e aprendizado em segurança cibernética. Qualquer uso indevido deste código para práticas ilegais é estritamente proibido e pode levar a consequências legais severas.

---

## 🚀 **O que é um ransomware?**
Ransomware é um tipo de malware que criptografa os arquivos de uma vítima, exigindo um pagamento (geralmente em criptomoedas) para fornecer a chave de descriptografia. Este projeto simula o funcionamento básico de um ransomware, como criptografia de arquivos e geração de chaves, para fins de pesquisa e conscientização.

---

## 🛠️ **Funcionalidades**
- **Criptografia de Arquivos:** Criptografa arquivos-alvo em um diretório específico usando o algoritmo AES (Advanced Encryption Standard).  
- **Geração de Chave:** Gera uma chave única para criptografia e descriptografia.  
- **Descriptografia:** Código para reverter a criptografia com a chave correta.

---

## 📋 **Como funciona?**
### Etapas:  
1. **Criptografia:** Os arquivos são criptografados usando o encrypter.py.  
2. **Descriptografia:** Os arquivos podem ser restaurados com o decrypter.py.

---

## ⚙️ **Como executar**
1. **Execute o ransomware:**  
   **⚠️ Aviso:** Certifique-se de usar um ambiente seguro e isolado (máquina virtual ou sandbox) para testes.
   
   ```bash
   python encrypter.py
   ```
3. **Descriptografia:**  
   Para reverter a criptografia, forneça a chave correta no script de descriptografia:
   
   ```bash
   python decrypter.py
   ```

---

## 🔒 **Medidas de Segurança Recomendadas**
Este projeto também serve para conscientizar sobre como proteger sistemas contra ransomware:  
- **Mantenha backups frequentes de seus dados.**  
- **Use softwares de proteção contra malware.**  
- **Evite abrir links ou anexos suspeitos.**  
- **Mantenha seu sistema operacional e software atualizados.**  

---
