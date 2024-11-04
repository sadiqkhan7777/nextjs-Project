// navbar.tsx

// import React from "react";
// import { FaHamburger } from "react-icons/fa";
// import { FaSearch } from "react-icons/fa";
// import { FaBolt } from "react-icons/fa";
// import { FaCartPlus } from "react-icons/fa";

// export default function Navbar() {
//   return (
//     <div>
//       <div className="grid xl:grid-cols-1 grid-cols-1">
//         <div className="p-5">
//           <div className="py-3 px-3 rounded-xl border w-full">
//             <div className="flex justify-between items-center">
//               <div className="flex justify-items-center items-center gap-2 ">
//                 {/* logo burger */}
//                 <FaHamburger className="w-6 h-6 text-yellow-400 hover:text-cyan-300" />

//                 {/* Search Icon */}
//                 <div style={{ position: "relative" }}>
//                   <input
//                     className="rounded-3xl py-3 px-3 outline-none text-xs w-[350px] pr-10 hidden lg:block md:block"
//                     placeholder="Search for your favorite burger from the menu"
//                   />

//                   <FaSearch className="w-5 h-5 text-lime-500 absolute right-3 top-1/2 transform -translate-y-1/2 hidden lg:block md:block" />
//                 </div>
//               </div>

//               <div className="flex justify-items-center gap-2">
//                 <FaBolt className="w-5 h-5 text-amber-400 lg:block md:block" />
//                 <p className="text-xs text-white hidden lg:block md:block">
//                   {" "}
//                   order now and get it fast in
//                   <span className="text-amber-400"> 15 minutes</span>
//                 </p>
              

//               {/* Cart icon */}
//               <FaCartPlus className="w-8 h-8 text-sky-400 rounded-full ring-2 p-1 relative hover:text-amber-400" />
//               <img
//                 className="inline-block w-8h-8 rounded-full ring-2 ring-sky-400 hover:text-amber-400"
//                 src="/images/capture.png"
//                 alt="user avatar"
//               />
//               </div>
//             </div>
//           </div>
//         </div>
//       </div>
//     </div>
//   );
// }