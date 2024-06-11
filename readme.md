```readme
fauzira alpiandi
```

```readme
just an enthusiastic...
```

```readme
frontend developer processing coffee into code,
thirsty for knowledge and pursued by curiosity.
```

```javascript
interface Profile {
  username: string;
  name: string;
  bio: string;
  location: string;
  email: string;
  website: string;
  social: { [key: string]: string };
  skills: string[];
  projects: { name: string; url: string }[];
  education: { degree: string; university: string; graduationYear: number };
  workExperience: { title: string; company: string; startDate: string }[];
}

const profile: Profile = {
  username: "username",
  name: "Nama Anda",
  bio: "Deskripsi singkat tentang Anda",
  location: "Lokasi Anda",
  email: "email@example.com",
  website: "https://websiteanda.com",
  social: { twitter: "@username", linkedin: "https://www.linkedin.com/in/username" },
  skills: ["JavaScript", "Node.js", "React"],
  projects: [{ name: "Project 1", url: "https://github.com/username/project1" }],
  education: { degree: "Gelar Anda", university: "Nama Universitas", graduationYear: 2022 },
  workExperience: [{ title: "Pekerjaan Anda", company: "Nama Perusahaan", startDate: "Jan 2020" }],
};

export default profile;
```