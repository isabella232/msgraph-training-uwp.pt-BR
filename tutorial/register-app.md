<!-- markdownlint-disable MD002 MD041 -->

<span data-ttu-id="f77dd-101">Neste exercício, você criará um novo aplicativo nativo do Azure AD usando o centro de administração do Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f77dd-101">In this exercise you will create a new Azure AD native application using the Azure Active Directory admin center.</span></span>

1. <span data-ttu-id="f77dd-102">Abra um navegador e navegue até o [centro de administração do Azure Active Directory](https://aad.portal.azure.com) e faça logon usando uma **conta pessoal** (aka: conta da Microsoft) ou **conta corporativa ou de estudante**.</span><span class="sxs-lookup"><span data-stu-id="f77dd-102">Open a browser and navigate to the [Azure Active Directory admin center](https://aad.portal.azure.com) and login using a **personal account** (aka: Microsoft Account) or **Work or School Account**.</span></span>

1. <span data-ttu-id="f77dd-103">Selecione **Azure Active Directory** na navegação à esquerda e, em seguida, selecione **registros de aplicativo (visualização)** em **gerenciar**.</span><span class="sxs-lookup"><span data-stu-id="f77dd-103">Select **Azure Active Directory** in the left-hand navigation, then select **App registrations (Preview)** under **Manage**.</span></span>

    ![<span data-ttu-id="f77dd-104">Uma captura de tela dos registros de aplicativo</span><span class="sxs-lookup"><span data-stu-id="f77dd-104">A screenshot of the App registrations</span></span> ](./images/aad-portal-app-registrations.png)

1. <span data-ttu-id="f77dd-105">Selecione **novo registro**.</span><span class="sxs-lookup"><span data-stu-id="f77dd-105">Select **New registration**.</span></span> <span data-ttu-id="f77dd-106">Na página **registrar um aplicativo** , defina os valores da seguinte maneira.</span><span class="sxs-lookup"><span data-stu-id="f77dd-106">On the **Register an application** page, set the values as follows.</span></span>

    - <span data-ttu-id="f77dd-107">Defina \*\*\*\* o nome `UWP Graph Tutorial`como.</span><span class="sxs-lookup"><span data-stu-id="f77dd-107">Set **Name** to `UWP Graph Tutorial`.</span></span>
    - <span data-ttu-id="f77dd-108">Defina os **tipos de conta com suporte** para **contas em qualquer diretório organizacional e contas pessoais da Microsoft**.</span><span class="sxs-lookup"><span data-stu-id="f77dd-108">Set **Supported account types** to **Accounts in any organizational directory and personal Microsoft accounts**.</span></span>
    - <span data-ttu-id="f77dd-109">Deixe o **URI** de redirecionamento vazio.</span><span class="sxs-lookup"><span data-stu-id="f77dd-109">Leave **Redirect URI** empty.</span></span>

    ![Uma captura de tela da página registrar um aplicativo](./images/aad-register-an-app.png)

1. <span data-ttu-id="f77dd-111">Escolha **registrar**.</span><span class="sxs-lookup"><span data-stu-id="f77dd-111">Choose **Register**.</span></span> <span data-ttu-id="f77dd-112">Na página do **tutorial do gráfico UWP** , copie o valor da **ID do aplicativo (cliente)** e salve-o, você precisará dele na próxima etapa.</span><span class="sxs-lookup"><span data-stu-id="f77dd-112">On the **UWP Graph Tutorial** page, copy the value of the **Application (client) ID** and save it, you will need it in the next step.</span></span>

    ![Uma captura de tela da ID do aplicativo do novo registro de aplicativo](./images/aad-application-id.png)

1. <span data-ttu-id="f77dd-114">Selecione o link **Adicionar um URI** de redirecionamento.</span><span class="sxs-lookup"><span data-stu-id="f77dd-114">Select the **Add a Redirect URI** link.</span></span> <span data-ttu-id="f77dd-115">Na página **redirecionar URIs** , localize a seção reDirecionar **URIs sugeridos para clientes públicos (móvel, área de trabalho)** .</span><span class="sxs-lookup"><span data-stu-id="f77dd-115">On the **Redirect URIs** page, locate the **Suggested Redirect URIs for public clients (mobile, desktop)** section.</span></span> <span data-ttu-id="f77dd-116">Selecione o `urn:ietf:wg:oauth:2.0:oob` URI e, em seguida, escolha **salvar**.</span><span class="sxs-lookup"><span data-stu-id="f77dd-116">Select the `urn:ietf:wg:oauth:2.0:oob` URI, then choose **Save**.</span></span>

    ![Captura de tela da página URIs de reDirecionamento](./images/aad-redirect-uris.png)