---
title: 'Karis v1.0.2 – Personal Blog & Magazine WordPress Theme'
date: 2020-01-02T11:50:00+01:00
draft: false
---

**Kang Asu**

[![](https://1.bp.blogspot.com/-Dvro6hT3DPE/XgJ7kr0JCtI/AAAAAAAARSI/nySEU2ZiG8czghfEdRWNibR8EKHAQdpyQCNcBGAsYHQ/s640/pown.png)](https://1.bp.blogspot.com/-Dvro6hT3DPE/XgJ7kr0JCtI/AAAAAAAARSI/nySEU2ZiG8czghfEdRWNibR8EKHAQdpyQCNcBGAsYHQ/s1600/pown.png)

**Pown.js - A Security Testing An Exploitation Toolkit Built On Top Of Node.js And NPM**

  

  
Pown.js is a security testing and [exploitation](https://www.kitploit.com/search/label/Exploitation "exploitation") toolkit built on top of Node.js and NPM. Unlike traditional security tools like Metasploits, Pown.js considers frameworks to be an anti-pattern. Therefore, each module in Pown is in fact a standalone NPM module allowing greater degree of reuse and flexibility. Creating new modules is a matter of publishing to NPM and tagging it with the correct tags. The rest is handled automatically.  
  
**Quickstart**  
Install Pown.js globally with npm or yarn.

```
$ npm install -g pown@latest
```

  
**Usage**

```
pown [options]  [command options]  
  
Commands:  
  pown modules                Module manager  [aliases: module, m]  
  pown update [options]                Update global installation of pown  [aliases: upgrade, up]  
  pown buster                 Multi-service [bruteforce](https://www.kitploit.com/search/label/Bruteforce "bruteforce") discovery tool  [aliases: bust]  
  pown credits [options]               list contributors and credits  
  pown dicts [options]         Assorted Dictionaries  
  pown duct                   Side-channel attack enabler  [aliases: ducting, d]  
  pown figlet                    Generate figlet  
  pown preferences            Preferences  [aliases: prefs]  
  pown proxy [options] [command]       HTTP proxy  
  pown recon                  Target recon  
  pown script [file   |script] [args...]  Simple scripting engine for automating pown commands.  
  pown shell [options]                 Simple shell  
  pown whoarethey         find social [networking](https://www.kitploit.com/search/label/Networking "networking") accounts and more  
  
Options:  
  --version  Show version number  [boolean]  
  --help     Show help  [boolean]
```

  
**`pown modules`**

```
pown modules   
  
Module manager  
  
Commands:  
  pown modules install     Install modules  
  pown modules uninstall   Uninstall modules  
  pown modules update [modules...]     Update modules  
  pown modules list                    List install modules  
  pown modules search        Search modules  
  
Options:  
  --version  Show version number  [boolean]  
  --help     Show help  [boolean]
```

  
**`pown update`**

```
pown update [options]  
  
Update global installation of pown  
  
Options:  
  --version  Show version number  [boolean]  
  --help     Show help  [boolean]
```

  
**`pown buster`**

```
pown buster   
  
Multi-service bruteforce discovery tool  
  
Commands:  
  pown buster web [options]        Web file and directory [bruteforcer](https://www.kitploit.com/search/label/Bruteforcer "bruteforcer") (a.k.a dirbuster)  
  pown buster email [options]   Email bruteforce discovery tool (via smtp)  [aliases: emails]  
  
Options:  
  --version  Show version number  [boolean]  
  --help     Show help  [boolean]
```

  
**`pown credits`**

```
pown credits [options]  
  
list contributors and credits  
  
Options:  
  --version   Show version number  [boolean]  
  --help      Show help  [boolean]  
  --only, -o  Only Pown.js contributors  [boolean]
```

  
**`pown dicts`**

```
pown dicts [options]   
  
Assorted Dictionaries  
  
Options:  
  --version       Show version number  [boolean]  
  --help          Show help  [boolean]  
  --download, -d  Download found dictionaries  [boolean] [default: false]  
  --regex, -r     Search with regex  [boolean] [default: false]
```

  
**`pown duct`**

```
pown duct   
  
Side-channel attack enabler  
  
Commands:  
  pown duct dns  DNS ducting  
  
Options:  
  --version  Show version number  [boolean]  
  --help     Show help  [boolean]
```

  
**`pown figlet`**

```
pown figlet   
  
Generate figlet  
  
Options:  
  --version   Show version number  [boolean]  
  --help      Show help  [boolean]  
  --font, -f  FIGlet font to use  [string] [default: "Standard"]  
  --fg        Foreground color  [choices: "default", "black", "red", "green", "yellow", "blue", "magenta", "cyan", "white", "gray", "grey"] [default: "default"]  
  --bg        Background color  [choices: "default", "black", "red", "green", "yellow", "blue", "magenta", "cyan", "white"] [default: "default"]  
  --bold      Make it bold  [boolean] [default: false]
```

  
**`pown preferences`**

```
pown preferences   
  
Preferences  
  
Commands:  
  pown preferences get  [name]          get preferences  
  pown preferences set     set preferences  
  
Options:  
  --version  Show version number  [boolean]  
  --help     Show help  [boolean]
```

  
**`pown proxy`**

```
pown proxy [options] [command]  
  
HTTP proxy  
  
Options:  
  --version                 Show version number  [boolean]  
  --help                    Show help  [boolean]  
  --log, -l                 Log requests and responses  [boolean] [default: false]  
  --host, -h                Host to listen to  [string] [default: "0.0.0.0"]  
  --port, -p                Port to listen to  [number] [default: 8080]  
  --text, -t                Start with text ui  [boolean] [default: false]  
  --ws-client, -c           Connect to web socket  [string] [default: ""]  
  --ws-server, -s           Forward on web socket  [boolean] [default: false]  
  --ws-host                 Web socket server host  [string] [default: "0.0.0.0"]  
  --ws-port                 Web socket server port  [number] [default: 9090]  
  --ws-app                  Open app  [string] [choices: "", "httpview"] [default: ""]  
  --certs-dir               Directory for the [certificates](https://draft.blogger.com/ht%20%20%20tps://www.kitploit.com/search/label/Certificates "certificates")  [string] [default: "/home/ec2-user/.pown/proxy/certs"]  
  --server-key-length       Default key length for certificates  [number] [default: 1024]  
  --default-ca-common-name  The CA common name  [string] [default: "Pown.js Proxy"]
```

  
**`pown recon`**

```
pown recon   
  
Target recon  
  
Commands:  
  pown recon transform         Perform inline transformation  [aliases: t]  
  pown recon select         Select nodes  [aliases: s]  
  pown recon add                Add nodes  [aliases: a]  
  pown recon remove         Remove nodes  [aliases: r]  
  pown recon merge              Perform a merge between at least two recon files  [aliases: m]  
  pown recon diff           Perform a diff between two recon files  [aliases: d]  
  pown recon group    Group nodes  [aliases: g]  
  pown recon ungroup        Ungroup nodes  [aliases: u]  
  pown recon import                 Import file  [aliases: i]  
  pown recon export                 Export to file  [aliases: e]  
  
Options:  
  --version  Show    version number  [boolean]  
  --help     Show help  [boolean]
```

  
**`pown script`**

```
pown script [file|script] [args...]  
  
Simple scripting engine for automating pown commands.  
  
Options:  
  --version      Show version number  [boolean]  
  --help         Show help  [boolean]  
  --command, -c  Evaluate inline commands  [boolean] [default: false]  
  --exit, -e     Exit immediately  [boolean] [default: false]  
  --expand, -x   Expand command  [boolean] [default: false]  
  --skip, -s     Skip number of lines  [number] [default: 0]
```

  
**`pown shell`**

```
pown shell [options]  
  
Simple shell  
  
Options:  
  --version  Show version number  [boolean]  
  --help     Show help  [boolean]
```

  
**`pown whoarethey`**

```
pown whoarethey   
  
find social networking accounts and more  
  
Options:  
  --version  Show version number  [boolean]  
  --help     Show help  [boolean]
```

  
**Modules**  
Pown.js comes with several builtin modules for convenience. However, additional modules can be installed directly from the NPM registry using `pown modules` command. Optional modules are installed in the current users's home folder under `.pown/modules`.  
  

**[Download Pown](http://libittarc.com/3E6o "Download Pown")**

**  
Regards**

**Kang Asu**