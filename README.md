

 Active-Recon-Module

The Active Recon Module is a lightweight Python-based toolkit designed for direct, interactive information gathering during penetration testing and red team engagements. It actively probes the target to discover open ports, identify running services, and detect technologies, making it effective for identifying potential attack surfaces.

---
   📁 Project Structure



Active-Recon-Module/
├── scripts/
│   ├── port\_scan.py         # TCP port scanning using Python sockets
│   ├── banner\_grab.py       # Service banner grabbing from open ports
│   └── tech\_detect.py       # Technology detection via HTTP headers
├── requirements.txt         # All dependencies listed here
├── README.md                # You're reading it!
├── LICENSE                  # MIT License
└── .gitignore               # Python cache and environment exclusions

`

---

         🚀 Features

✅ Port Scanning (common ports using sockets)  
✅ Banner Grabbing (service/version identification)  
✅ Technology Detection (via HTTP headers)  
✅ Clean, modular scripts (easy to integrate into other tools)  
✅ CLI-ready (can be used manually or integrated into larger frameworks)

---

                   ⚙ Setup Instructions

 1. Clone the repository
bash
git clone https://github.com/mahadzulfiqar/Active-Recon-Module.git
cd Active-Recon-Module
`

 2. Install dependencies

Use a virtual environment (recommended):

bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt


                   🧪 How to Use
 Port Scanning

bash
python scripts/port_scan.py


 Banner Grabbing

bash
python scripts/banner_grab.py


 Technology Detection

bash
python scripts/tech_detect.py


Each script will prompt for a target domain/IP and port where applicable.

                     📦 Dependencies

* `requests` (for HTTP-based detection)

Install them using:

bash
pip install -r requirements.txt

                       📜 License

This project is licensed under the MIT License. See `LICENSE` for more details.

---

                         ✍ Author

**Mahad Zulfiqar**
Cybersecurity Intern | [GitHub](https://github.com/mahadzulfiqar) | [LinkedIn](https://linkedin.com)



                         🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

 Disclaimer

This tool is intended for educational and authorized penetration testing purposes only.
**Do not use it on systems or networks you do not own or have explicit permission to test.**



