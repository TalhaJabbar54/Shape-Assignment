# Shape-Assignment
Signup Page to register users using API.
Project is developed on ASP.NET Core MVC 5.0.
I have attached two zip files one is BAK file of registrationDb and one is ShapeAssignment which is a complete .Net Core Project.

Sql Script of table:
USE [RegistrationDB]
GO

/****** Object:  Table [dbo].[UserRegistration]    Script Date: 14/10/2022 5:48:10 pm ******/
SET ANSI_NULLS ON
GO

SET QUOTED_IDENTIFIER ON
GO

CREATE TABLE [dbo].[UserRegistration](
	[UserId] [int] IDENTITY(1,1) NOT NULL,
	[FirstName] [nvarchar](250) NOT NULL,
	[LastName] [nvarchar](250) NOT NULL,
	[EmailAddress] [nvarchar](250) NOT NULL,
	[Password] [nvarchar](250) NOT NULL,
	[ConfPass] [nvarchar](250) NOT NULL,
 CONSTRAINT [PK_UserRegistration] PRIMARY KEY CLUSTERED 
(
	[UserId] ASC
)WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS = ON, ALLOW_PAGE_LOCKS = ON, OPTIMIZE_FOR_SEQUENTIAL_KEY = OFF) ON [PRIMARY]
) ON [PRIMARY]
GO







