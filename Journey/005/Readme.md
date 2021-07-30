# Day 5 - Preparing Azure for AADDS Deployment

## Introduction

Today is Day 5 of 100 Days of Cloud. Today's post is about preparing the Azure environment for an Azure Active Directory Domain Services (AADDS) deployment. There are quite a few moving pieces to a proper AADDS deployment. To keep things organized and clean, today I created an AADDS-specific Resource Group, Virtual Network and Subnet.

## Prerequisite

Knowledge and familiarity with the Azure portal, Resource Groups, Networking and Subnetting.

## Use Case

Active Directory is and has been very popular for a long time. Azure Active Directory Domain Services (AADDS) is NOT Active Directory in the cloud. In a hybrid environment AADDS is a staple, a necessity. The simplest explanation of AADDS I have heard is that it is basically a Domain Controller (DC) done as a PaaS service. Unlike a regular DC, there is no management as it basically takes care of itself and provides NTLM/Kerberos/DNS/LDAP/etc.

## Objective Demonstration & Screenshots

The daily objective, notes and screenshots can be seen in the blog post below.

[Tweet](https://twitter.com/LogPhile/status/1415059051923353603)

[Blog](https://logphile.com/2021/07/26/100daysofcloud-day-5-preparing-azure-for-aads-1-of-4/)
