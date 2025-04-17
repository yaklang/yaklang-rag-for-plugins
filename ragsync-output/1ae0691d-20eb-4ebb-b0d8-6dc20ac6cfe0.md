# 通用漏洞（General）
# SEO
JWT,Token,加密算法,漏洞检测。JWT,Token,Encryption Algorithm,Vulnerability Detection
# Summary
该插件用于检测JWT Token的算法校验漏洞，通过将加密算法修改为None，生成新的Token并替换原Token，观察返回内容是否变化来判断是否存在漏洞。。This plugin is used to detect JWT Token algorithm verification vulnerabilities by modifying the encryption algorithm to None, generating a new Token and replacing the original Token, and determining if a vulnerability exists by observing whether the response content changes.
