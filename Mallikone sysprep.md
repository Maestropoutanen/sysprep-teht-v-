
# Työaseman automatisointi ohjeet  

* Audit tilaan pääset painamalla näppäinyhdistelmää(CTRl, shift ja F3)  

* Ennen syspreppausta on työasemasta muutettava verkkoasetukset sekä halutessa ladata (bginfo) sovellus ja muokata sen haluttavan näköiseksi. Windows on myös päivitettävä ajan tasalle. Myös on ladattava ADK sovellus jotta voit tehdä vastaustiedoston.   

* Ekana avaat järjestelmä valvojan komentokehotteen ja haet sieltä kansion missä sysprep sijaitsee yleensä, C:/Windows/system32/sysprep. Myös pitää muistaa kopioida adk sovelluksella tehty vastaustideosto kansioon. Sitten syötät komentokehotteeseen komennonsysprep /generalize /oobe /shutdown /unattend:sysprepunattend.xml  

![kuva vastaustiedostosta](vastaustiedosto.png)


