### About me
```go
package main

import "fmt"

type Person struct {
    Name                 string
    Role                 string
    Languages            []string
    ProgrammingLanguages []string
    DevOpsTools          []string
}

func (p Person) Greet() {
    fmt.Printf("Hello my name is %v and my role at my current job is %s\n", p.Name, p.Role)

    fmt.Println("\nI speak:")
    for _, lang := range p.Languages {
        fmt.Printf("- %s\n", lang)
    }

    fmt.Println("\nI program in:")
    for _, progLang := range p.ProgrammingLanguages {
        fmt.Printf("- %s\n", progLang)
    }

    fmt.Println("\nI work with the following DevOps tools and technologies:")
    for _, tool := range p.DevOpsTools {
        fmt.Printf("- %s\n", tool)
    }

    fmt.Println("\nThanks for dropping by, hope you find some of my work interesting. 👋")
}

func main() {
    me := Person {
        Name:                 "Huszár Bence",
        Role:                 "DevOps Engineer",
        Languages:            []string{"hu_HU", "en_US"},
        ProgrammingLanguages: []string{"GO", "Lua", "PHP", "Python", "C#", "jQuery", "HTML", "CSS", "JavaScript"},
        DevOpsTools:          []string{"AWS", "Docker", "K8s", "Ansible", "traefik", "Nginx"},
    }

    me.Greet()
}
```
<p><em>DevOps Engineer at <a href="https://www.ehaz.hu/">eHÁZ</em></p>

### Operating systems I use(d)
<div>
<a href="https://archlinux.org"><img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white"></a>
<a href="https://www.microsoft.com/en-us/windows/?r=1"><img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"></a>
<a href="https://ubuntu.com/"><img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"></a>
<a href="https://www.centos.org/"><img src="https://img.shields.io/badge/Cent%20OS-262577?style=for-the-badge&logo=CentOS&logoColor=white"></a>
</div>

### Hypervisors I use(d)
<div>
<a href="https://www.proxmox.com/en/"><img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white"></a>
<a href="https://www.vmware.com/products/esxi-and-esx.html"><img src="https://img.shields.io/badge/VMware-231f20?style=for-the-badge&logo=VMware&logoColor=white"></a>
</div>
