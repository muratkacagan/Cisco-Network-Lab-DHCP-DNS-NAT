# Cisco Packet Tracer - Network Services & Routing Lab

Bu proje, Cisco Packet Tracer üzerinde ağ temellerini ve çeşitli ağ servislerini yapılandırdığım kapsamlı bir laboratuvar çalışmasıdır.

Proje İçeriği ve Yapılandırmalar
Bu topolojide adım adım aşağıdaki protokoller ve servisler yapılandırılmıştır:

DHCP Konfigürasyonu: Yerel ağdaki (192.168.1.0) istemcilere otomatik IP dağıtımı.
DHCP Relay (IP Helper): İki farklı ağ (Router) arasında DHCP yayınlarını iletme ve diğer ağdaki (192.168.2.0) istemciye IP aldırma.
Statik Yönlendirme: İki farklı router'ın seri haberleşme arayüzleri (s2/0) üzerinden birbiriyle haberleşmesi (`ip route 0.0.0.0 0.0.0.0 s2/0`).
DNS Sunucu Kurulumu: Yerel ağda İsim Çözümleme hizmeti yapılandırılarak `www.deney.com` alan adının bir HTTP sunucusuna (192.168.2.5) yönlendirilmesi.
NAT (Network Address Translation): Yerel (Private) IP adresine sahip DNS sunucusunu (192.168.2.5) dışarıdan erişilebilir kılmak için Global (Public) IP adresine (20.0.0.1) dönüştürme işlemi (Static NAT).

🛠️ Kullanılan Teknolojiler
Cisco Packet Tracer
CLI Yapılandırması 
Cisco IOS Network Commands

Projeyi Nasıl İnceleyebilirsiniz?
1. Bu repodaki `.pkt` uzantılı simülasyon dosyasını indirin.
2. Bilgisayarınızda yüklü olan Cisco Packet Tracer programı ile açın.
3. Cihazların CLI ekranından konfigürasyonları inceleyebilir veya simülasyon modunda ping testleri yapabilirsiniz.
