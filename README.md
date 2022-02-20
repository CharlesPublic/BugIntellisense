# BugIntellisense
TEMP Project to show an intellisense bug

Bug: "using statement" suggestions are missing for Extension methods  
for .NET 4.8 Projects when referenced from .NET 6 Projects


    "".Ext4_8();    // Intellisense doesn't work
    "".Ext6();      // Intellisense works

    ExtensionMethods4_8.Ext4_8("");      // Intellisense works
    ExtensionMethods6.Ext6("");          // Intellisense works
