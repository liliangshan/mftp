# MFTP - 智能FTP文件上传工具

[简体中文](#简体中文) | [English](#english) | [繁體中文](#繁體中文) | [日本語](#日本語) | [한국어](#한국어) | [Français](#français)

GitHub: [https://github.com/liliangshan/mftp](https://github.com/liliangshan/mftp)

## 简体中文

### 🚀 MFTP - 智能、高效的跨平台FTP同步工具

MFTP是一款开源的多语言FTP文件同步工具，专为开发者和系统管理员设计。它提供了轻量、快速、智能的文件同步解决方案。

#### ✨ 主要特性

1. **智能文件同步**
   - 仅同步发生变更的文件，类似Git的增量更新机制
   - 基于MD5快速检测文件变化
   - 支持跨平台（Windows/macOS/Linux）

2. **多语言支持**
   - 目前支持简体中文、英文、繁体中文、日语、韩语、法语
   - 一键切换语言，轻松使用

3. **简单易用**
   - 命令行界面，操作直观
   - 快速配置FTP连接
   - 支持交互式设置

4. **安全可靠**
   - 安全的文件传输
   - 详细的日志记录
   - 支持多种FTP服务器

#### 🛠 安装方法

```bash
# 使用Go安装
go clone https://github.com/liliangshan/mftp.git

# 或直接下载可执行文件
```

#### 🔧 使用示例

```bash
# 初始化配置
mftp

# 创建MD5索引
mftp index

# 检查文件状态
mftp status

# 切换语言
mftp --lang en-US
```

#### 📦 系统需求

- Go 1.16+
- 支持FTP的服务器

#### 🤝 贡献与支持

欢迎提交Issues和Pull Requests！

---

## English

### 🚀 MFTP - Intelligent Cross-Platform FTP Synchronization Tool

MFTP is an open-source, multilingual FTP file synchronization tool designed for developers and system administrators. It provides a lightweight, fast, and intelligent file synchronization solution.

#### ✨ Key Features

1. **Intelligent File Synchronization**
   - Sync only changed files, similar to Git's incremental update mechanism
   - Quickly detect file changes based on MD5
   - Cross-platform support (Windows/macOS/Linux)

2. **Multilingual Support**
   - Currently supports Chinese (Simplified/Traditional), English, Japanese, Korean, French
   - Easy language switching

3. **Simple and User-Friendly**
   - Intuitive command-line interface
   - Quick FTP connection configuration
   - Interactive setup support

4. **Secure and Reliable**
   - Secure file transfer
   - Detailed logging
   - Support for multiple FTP servers

#### 🛠 Installation

```bash
# Install via git
go clone https://github.com/liliangshan/mftp.git

# Or download executable directly
```

#### 🔧 Usage Examples

```bash
# Initialize configuration
mftp

# Create MD5 index
mftp index

# Check file status
mftp status

# Switch language
mftp --lang zh-CN
```

#### 📦 System Requirements

- Go 1.16+
- FTP-supported server

#### 🤝 Contribution and Support

Welcome to submit Issues and Pull Requests!

---

## 繁體中文

### 🚀 MFTP - 智慧、高效的跨平台FTP同步工具

MFTP是一款開源的多語言FTP檔案同步工具，專為開發者和系統管理員設計。它提供了輕量、快速、智慧的檔案同步解決方案。

#### ✨ 主要特色

1. **智慧檔案同步**
   - 僅同步變更的檔案，類似Git的增量更新機制
   - 基於MD5快速偵測檔案變化
   - 支援跨平台（Windows/macOS/Linux）

2. **多語言支援**
   - 目前支援簡體中文、英文、繁體中文、日語、韓語、法語
   - 一鍵切換語言，使用便利

3. **簡單易用**
   - 命令列介面，操作直觀
   - 快速設定FTP連線
   - 支援互動式設定

4. **安全可靠**
   - 安全的檔案傳輸
   - 詳細的日誌記錄
   - 支援多種FTP伺服器

#### 🛠 安裝方法

```bash
# 使用git安裝
git clone https://github.com/liliangshan/mftp.git

# 或直接下載可執行檔
```

#### 🔧 使用範例

```bash
# 初始化設定
mftp

# 建立MD5索引
mftp index

# 檢查檔案狀態
mftp status

# 切換語言
mftp --lang en-US
```

#### 📦 系統需求

- Go 1.16+
- 支援FTP的伺服器

#### 🤝 貢獻與支援

歡迎提交Issues和Pull Requests！

---

## 日本語

### 🚀 MFTP - インテリジェントなクロスプラットフォームFTP同期ツール

MFTPは、開発者とシステム管理者向けに設計されたオープンソースの多言語FTPファイル同期ツールです。軽量で高速、インテリジェントなファイル同期ソリューションを提供します。

#### ✨ 主な特徴

1. **インテリジェントなファイル同期**
   - Gitのような増分更新メカニズムで、変更されたファイルのみを同期
   - MD5ベースの高速なファイル変更検出
   - クロスプラットフォーム対応（Windows/macOS/Linux）

2. **多言語サポート**
   - 現在、中国語（簡体/繁体）、英語、日本語、韓国語、フランス語に対応
   - 簡単な言語切り替え

3. **シンプルで使いやすい**
   - 直感的なコマンドラインインターフェース
   - 迅速なFTP接続設定
   - インタラクティブな設定サポート

4. **安全で信頼性が高い**
   - 安全なファイル転送
   - 詳細なログ記録
   - 複数のFTPサーバーに対応

#### 🛠 インストール方法

```bash
# gitを使用してインストール
git clone https://github.com/liliangshan/mftp.git

# または実行ファイルを直接ダウンロード
```

#### 🔧 使用例

```bash
# 設定の初期化
mftp

# MD5インデックスの作成
mftp index

# ファイルステータスの確認
mftp status

# 言語の切り替え
mftp --lang en-US
```

#### 📦 システム要件

- Go 1.16+
- FTPをサポートするサーバー

#### 🤝 貢献とサポート

Issues and Pull Requestsを歓迎します！

---

## 한국어

### 🚀 MFTP - 지능형 크로스 플랫폼 FTP 동기화 도구

MFTP는 개발자와 시스템 관리자를 위해 설계된 오픈 소스 다국어 FTP 파일 동기화 도구입니다. 가볍고 빠르며 지능적인 파일 동기화 솔루션을 제공합니다.

#### ✨ 주요 기능

1. **지능형 파일 동기화**
   - Git과 유사한 증분 업데이트 메커니즘으로 변경된 파일만 동기화
   - MD5 기반의 빠른 파일 변경 감지
   - 크로스 플랫폼 지원 (Windows/macOS/Linux)

2. **다국어 지원**
   - 현재 중국어(간체/번체), 영어, 일본어, 한국어, 프랑스어 지원
   - 쉬운 언어 전환

3. **간단하고 사용자 친화적**
   - 직관적인 명령줄 인터페이스
   - 빠른 FTP 연결 구성
   - 대화형 설정 지원

4. **안전하고 신뢰할 수 있음**
   - 안전한 파일 전송
   - 상세한 로깅
   - 다양한 FTP 서버 지원

#### 🛠 설치 방법

```bash
# git를 사용하여 설치
git clone https://github.com/liliangshan/mftp.git

# 또는 실행 파일 직접 다운로드
```

#### 🔧 사용 예시

```bash
# 구성 초기화
mftp

# MD5 인덱스 생성
mftp index

# 파일 상태 확인
mftp status

# 언어 전환
mftp --lang en-US
```

#### 📦 시스템 요구 사항

- Go 1.16+
- FTP를 지원하는 서버

#### 🤝 기여 및 지원

Issues와 Pull Requests를 환영합니다!

---

## Français

### 🚀 MFTP - Outil de synchronisation FTP multilingue et intelligent

MFTP est un outil de synchronisation de fichiers FTP open-source et multilingue, conçu pour les développeurs et les administrateurs système. Il offre une solution de synchronisation de fichiers légère, rapide et intelligente.

#### ✨ Fonctionnalités principales

1. **Synchronisation de fichiers intelligente**
   - Synchronise uniquement les fichiers modifiés, similaire au mécanisme de mise à jour incrémentale de Git
   - Détection rapide des modifications de fichiers basée sur MD5
   - Support multiplateforme (Windows/macOS/Linux)

2. **Support multilingue**
   - Supporte actuellement le chinois (simplifié/traditionnel), anglais, japonais, coréen, français
   - Changement de langue facile

3. **Simple et convivial**
   - Interface en ligne de commande intuitive
   - Configuration rapide de la connexion FTP
   - Support de configuration interactive

4. **Sécurisé et fiable**
   - Transfert de fichiers sécurisé
   - Journalisation détaillée
   - Support de plusieurs serveurs FTP

#### 🛠 Installation

```bash
# Installer via git
git clone https://github.com/liliangshan/mftp.git

# Ou télécharger directement l'exécutable
```

#### 🔧 Exemples d'utilisation

```bash
# Initialiser la configuration
mftp

# Créer un index MD5
mftp index

# Vérifier l'état des fichiers
mftp status

# Changer de langue
mftp --lang en-US
```

#### 📦 Configuration requise

- Go 1.16+
- Serveur supportant FTP

#### 🤝 Contribution et support

N'hésitez pas à soumettre des Issues et des Pull Requests !