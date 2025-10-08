# Introduction to React Router

## Question
Ano ang React Router at para saan ito ginagamit?
## Answer
Ang React Router ay isang library na ginagamit sa mga React application upang makapagdagdag ng navigation o paglipat-lipat ng pahina nang hindi nire-reload ang buong website.



# Core Router Components

## Question
Ano ang pangunahing mga component na ginagamit sa React Router?
## Answer
BrowserRouter – nakapaloob sa buong app para paganahin ang routing.

Routes – container ng lahat ng ruta.

Route – tumutukoy sa isang partikular na path at component na ipapakita.



# Navigation Techniques

## Question
Paano nagna-navigate o lumilipat ng pahina sa React Router?
## Answer
Link component — ginagamit para sa mga link sa loob ng app (hal. <Link to="/about">About</Link>)

useNavigate() hook — ginagamit sa JavaScript upang programatikong lumipat ng ruta (hal. navigate('/home'))



# Dynamic Routes & Parameters

## Question
Ano ang dynamic routes sa React Router at paano ito ginagamit?
## Answer
Ang dynamic routes ay mga ruta na may variable na bahagi (parameter).
Halimbawa:

<Route path="/user/:id" element={<User />} />


Sa loob ng component, makukuha ang id gamit ang useParams() ho



# Nested Routes & Layouts

## Question
Ano ang nested routes at paano ito nakakatulong sa layout ng app?
## Answer
Ang nested routes ay mga ruta sa loob ng ibang ruta, na tumutulong upang makagawa ng layout na may shared components tulad ng header o sidebar.
Halimbawa:

<Route path="/dashboard" element={<Dashboard />}>
  <Route path="profile" element={<Profile />} />
</Route>


Sa ganitong paraan, may iisang layout ang parent route habang nag-iiba lang ang laman sa loob...