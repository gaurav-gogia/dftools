
<h1 align="center">
  DFTOOLS
</h1>

<h4 align="center">A curated list of Digital Forensics Tools with some useful links & usage.
To get information about any other tool please visit the  <a href="https://forensicswiki.org" target="_blank">Forensic Wiki</a>.</h4>


<h4 align="center"><a href=""><img src="./pics/df-transparent.png" alt="Forensics" width="200"></a></h4>


#### 📢 Some Important Concepts

- Digital Forensics: An applicaiton of science to uncover facts, solve crime by **acquiring** the evidence <br />
**analyzing** the evidence and finally prepping it for any court of law. All the steps must be completed while <br /> maintaining the [chain of custody](https://digital-forensics.sans.org/blog/tags/chain-of-custody) and **integrity**.

- Forensic Image/Copy: This term refers to a **bit perfect** copy/clone of any storage device.<br/>
It is important to understand that any forensic cloning tool worth it's salt would ensure integrity of evidence. <br />
This is why in forensic terms a simple backup is not enough.

- Data recovery tools look into unallocated sectors to find the files that were thought to be lost. They reach out <br />
to a very low level, below all the abstraction layers.

#### 📝 Forensic Copy
- [DC3DD](./dc3dd.md)
- [DD](https://wiki.archlinux.org/index.php/disk_cloning)
- [DCFLDD](https://www.forensicswiki.org/wiki/Dcfldd)
- [Guymager](./guymager.md)

#### ♻️ Data Recovery/Carving
- [Foremost](./foremost.md)
- [Bulk Extractor](./bulk_extractor.md)

#### 🈹 Multi-Purpose Kits
- [Autopsy](https://www.sleuthkit.org/autopsy/)

#### 📊 Metadata analysis
- [Exiftool](./exiftool.md)

#### 📟 Network Forensic Analysis Tool (NFAT)
-[Xplico](http://www.xplico.org/about)

#### :octocat: Contribution Guidelines
1. Fork the repository.
2. Clone it.
3. Create a new file explaining a digital forensic tool, if pics are involved please upload them in pics folder and link accordingly.
4. Make an entry about that tool in the main Readme File(this file).
5. Send PR.
6. Star this Repo
