
          <span className="text-base font-medium">{t("view-source-code")}</span>	            <span className="text-base font-medium">{t("view-source-code")}</span>
          </a>	          </a>


          <a	          <a className="flex items-center gap-2 mx-auto lg:ml-0" href="#" onClick={toggleTheme} id="theme-toggle">
            className="flex items-center gap-2 mx-auto lg:ml-0"	
            href="#"	
            onClick={toggleTheme}	
            id="theme-toggle"	
          >	
            <svg	            <svg
              id="theme-toggle-dark-icon"	              id="theme-toggle-dark-icon"
              className="w-5 h-5 hidden"	              className="w-5 h-5 hidden"
              fill="#2F80ED"	              fill="#2F80ED"
              viewBox="0 0 20 20"	              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"	              xmlns="http://www.w3.org/2000/svg
              ></path>	
            </svg>	            </svg>
            <svg	            <svg
              id="theme-toggle-light-icon"	              id="theme-toggle-light-icon"
@@ -140,7 +131,7 @@ export default function Layout({ children, lang }) {
        </div>	        </div>
      </div>	      </div>
      <div className="dark:bg-[#181818] bg-[#f3f3f3] p-5 relative flex flex-col gap-5">	      <div className="dark:bg-[#181818] bg-[#f3f3f3] p-5 relative flex flex-col gap-5"
        {children}	        {children}
      </div>	      </div>
  49 changes: 23 additions & 26 deletions49  
components/RPCList/index.js
@@ -81,7 +81,6 @@ export default function RPCList({ chain, lang }) {


  return (	  return (
    <div className="shadow dark:bg-[#0D0D0D] bg-white p-8 rounded-[10px] flex flex-col gap-3 overflow-hidden col-span-full relative overflow-x-auto">	    <div className="shadow dark:bg-[#0D0D0D] bg-white p-8 rounded-[10px] flex flex-col gap-3 overflow-hidden col-span-full relative overflow-x-auto">

      <table className="m-0 border-collapse whitespace-nowrap dark:text-[#B3B3B3] text-black">	      <table className="m-0 border-collapse whitespace-nowrap dark:text-[#B3B3B3] text-black">
        <caption className="relative w-full px-3 py-1 text-base font-medium border border-b-0">	        <caption className="relative w-full px-3 py-1 text-base font-medium border border-b-0">
          <span className="mr-4">{`${chain.name} RPC URL List`}</span>	          <span className="mr-4">{`${chain.name} RPC URL List`}</span>
@@ -120,22 +119,22 @@ export default function RPCList({ chain, lang }) {


        <tbody>	        <tbody>
          {rpcData.map((item, index) => {	          {rpcData.map((item, index) => {
            let className = 'bg-inherit';	            let className = "bg-inherit";


            }	            }


            return (	            return (
              <Row	              <Row
                values={item}	                values={item}
                chain={chain}	                chain={chain}
                key={index}	                key={item.data.url + chain + lang}dante7777777/dante7777777 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
i love github haha
do u know me ??
haha
rop 
attach file bye dragging and dropping selecting or posing the, dsacfas
