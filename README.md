## primeiro passo
### modificar o Register.cshtml.cs
#### incluir na InputModel:
    [Required]
    [Display(Name = "Nome")]
    public string UserName { get; set; }

## segundo passo
### modificar o método OnPostAsync

## terceiro passo
### incluir o input na View Register.cshtml

## quarto passo
### modificar o construtor do Login.cshtml.cs

## quinto passo
### modificar o método OnPostAsync do Login.cshtml.cs
É injetado o _userManager no construtor

## sexto passo
### modificar o Program.cs
Modificação realizada para permitir espaços na input UserName
