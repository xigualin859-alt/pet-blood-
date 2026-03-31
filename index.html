/**
 * @license
 * SPDX-License-Identifier: Apache-2.0
 */

import React, { useState, useEffect } from 'react';
import { 
  HeartPulse, Home, User, AlertCircle, MapPin, Activity, Medal, 
  ChevronRight, ChevronLeft, Phone, Search, Bell, Settings, Share2, 
  Camera, FileText, CheckCircle, XCircle, Map, Award, Star, Clock, Shield,
  QrCode, Navigation, ArrowRight, Heart, Droplet, MessageCircle
} from 'lucide-react';
import { motion, AnimatePresence } from 'motion/react';

// --- Mock Data ---
const petProfile = {
  name: "奥利奥 (Oreo)",
  breed: "边境牧羊犬",
  bloodType: "DEA 1.1 阳性",
  avatar: "🐶",
  donations: 3,
  points: 1250,
  badges: ["初级救护员", "勇敢汪星人", "健康满分"]
};

// --- Common Components ---
const TopBar = ({ title, onBack, rightIcon }: { title: string; onBack: () => void; rightIcon?: React.ReactNode }) => (
  <div className="flex items-center justify-between p-4 bg-white sticky top-0 z-40 border-b border-gray-100">
    <button onClick={onBack} className="p-2 -ml-2 text-gray-600 hover:bg-gray-50 rounded-full transition-colors">
      <ChevronLeft size={24} />
    </button>
    <h1 className="text-lg font-bold text-gray-800">{title}</h1>
    <div className="w-10 flex justify-end">
      {rightIcon && <button className="text-gray-600 p-2">{rightIcon}</button>}
    </div>
  </div>
);

export default function App() {
  const [currentView, setCurrentView] = useState('splash');
  const [currentTab, setCurrentTab] = useState('home');

  const navigate = (view: string) => {
    window.scrollTo(0, 0);
    setCurrentView(view);
  };

  const switchTab = (tab: string) => {
    setCurrentTab(tab);
    setCurrentView('main');
  };

  const NotificationsView = () => (
    <div className="min-h-screen bg-slate-50">
      <TopBar title="消息中心" onBack={() => navigate('main')} rightIcon={<CheckCircle size={20}/>} />
      <div className="p-4 space-y-3">
        <div className="bg-white p-4 rounded-2xl flex items-start opacity-60">
          <div className="bg-orange-100 p-2 rounded-full mr-3 text-orange-500"><Bell size={20}/></div>
          <div>
            <h4 className="text-sm font-bold text-gray-800">周边求助警报已解除</h4>
            <p className="text-xs text-gray-500 mt-1">您3小时前收到的求助信息（金毛Max）已成功匹配到血源，感谢您的关注！</p>
            <p className="text-[10px] text-gray-400 mt-2">今天 10:30</p>
          </div>
        </div>
        <div className="bg-white p-4 rounded-2xl flex items-start relative border-l-4 border-teal-500 shadow-sm">
          <div className="absolute top-4 right-4 w-2 h-2 bg-red-500 rounded-full"></div>
          <div className="bg-teal-100 p-2 rounded-full mr-3 text-teal-600"><FileText size={20}/></div>
          <div>
            <h4 className="text-sm font-bold text-gray-800">奥利奥的体检报告已出</h4>
            <p className="text-xs text-gray-500 mt-1">10月15日的献血前全套生化报告已生成，各项指标优秀，点击查看。</p>
            <p className="text-[10px] text-gray-400 mt-2">昨天 18:20</p>
          </div>
        </div>
      </div>
    </div>
  );

  const LeaderboardView = () => (
    <div className="min-h-screen bg-white">
      <TopBar title="城市英雄榜" onBack={() => navigate('main')} />
      <div className="bg-teal-500 pt-6 pb-12 px-6 text-center text-white rounded-b-[40px]">
        <h2 className="text-2xl font-bold mb-8">10月深圳献血之星</h2>
        <div className="flex justify-center items-end gap-4">
          <div className="flex flex-col items-center">
            <div className="w-16 h-16 bg-gray-200 rounded-full border-2 border-slate-300 relative flex items-center justify-center text-2xl">
              🐱<div className="absolute -bottom-3 bg-slate-400 text-white text-[10px] px-2 py-0.5 rounded-full font-bold">NO.2</div>
            </div>
            <p className="mt-4 text-sm font-bold">布丁</p>
            <p className="text-xs text-teal-200">4次救助</p>
          </div>
          <div className="flex flex-col items-center mb-4">
            <div className="w-24 h-24 bg-yellow-100 rounded-full border-4 border-yellow-400 shadow-[0_0_15px_rgba(250,204,21,0.5)] relative flex items-center justify-center text-4xl">
              🦮<Award size={32} className="absolute -top-4 text-yellow-400 drop-shadow-md" />
              <div className="absolute -bottom-3 bg-yellow-500 text-white text-xs px-3 py-0.5 rounded-full font-bold">NO.1</div>
            </div>
            <p className="mt-4 font-bold text-lg">Max</p>
            <p className="text-xs text-teal-100">6次救助</p>
          </div>
          <div className="flex flex-col items-center">
            <div className="w-16 h-16 bg-gray-200 rounded-full border-2 border-orange-300 relative flex items-center justify-center text-2xl">
              🐶<div className="absolute -bottom-3 bg-orange-400 text-white text-[10px] px-2 py-0.5 rounded-full font-bold">NO.3</div>
            </div>
            <p className="mt-4 text-sm font-bold">豆豆</p>
            <p className="text-xs text-teal-200">3次救助</p>
          </div>
        </div>
      </div>
      
      <div className="px-6 py-4 -mt-6">
        <div className="bg-white rounded-2xl shadow-lg p-2">
          {[4, 5, 6].map(num => (
            <div key={num} className="flex items-center p-3 border-b border-gray-50 last:border-0">
              <span className="w-6 font-bold text-gray-400">{num}</span>
              <div className="w-10 h-10 bg-gray-100 rounded-full flex items-center justify-center mr-3">🐕</div>
              <div className="flex-1"><p className="text-sm font-bold text-gray-800">毛毛 (哈士奇)</p></div>
              <div className="text-right"><p className="text-sm font-bold text-teal-600">2次</p></div>
            </div>
          ))}
        </div>
      </div>
    </div>
  );

  const ArticleDetailView = () => (
    <div className="min-h-screen bg-white pb-20">
      <TopBar title="科普百科" onBack={() => navigate('main')} rightIcon={<Share2 size={20}/>} />
      <div className="w-full h-48 bg-red-50 flex items-center justify-center">
        <HeartPulse size={64} className="text-red-200" />
      </div>
      <div className="p-6">
        <h1 className="text-2xl font-bold text-gray-800 mb-3">宠物血型全指南：A型、B型还是AB型？</h1>
        <div className="flex items-center text-xs text-gray-400 mb-6">
          <span>PawsLife 医疗组</span> <span className="mx-2">·</span> <span>阅读 1.2w</span>
        </div>
        <div className="text-gray-600 text-sm leading-relaxed space-y-4">
          <p>就像人类一样，我们的毛孩子们也有自己的血型。了解宠物的血型，在紧急需要输血时是拯救生命的关键。</p>
          <h3 className="text-base font-bold text-gray-800 mt-6">🐱 猫咪的血型系统</h3>
          <p>猫咪主要有A型、B型和罕见的AB型。A型是最常见的（约占95%），而B型在某些纯种猫（如英国短毛猫）中更常见。猫咪体内含有天然的同种抗体，这意味着输错血型会导致致命的反应！</p>
          <h3 className="text-base font-bold text-gray-800 mt-6">🐶 狗狗的血型系统</h3>
          <p>狗狗的血型被称为 DEA（狗红细胞抗原）系统。最重要的一种是 DEA 1.1。DEA 1.1 阴性的狗狗被认为是“万能供血者”，而 DEA 1.1 阳性的狗狗只能接受阳性血液。</p>
          <div className="bg-teal-50 p-4 rounded-xl text-teal-800 mt-6 border border-teal-100">
            <strong>💡 小贴士：</strong>
            强烈建议在宠物年轻健康时，进行一次常规血型检测，并在APP中完善档案。
          </div>
        </div>
      </div>
    </div>
  );

  const SOSRadarView = () => (
    <div className="p-6 min-h-screen bg-gray-900 flex flex-col items-center justify-center relative overflow-hidden text-white">
      <div className="absolute w-64 h-64 border-4 border-orange-500/20 rounded-full animate-ping"></div>
      <div className="absolute w-[400px] h-[400px] border-2 border-orange-500/10 rounded-full animate-ping" style={{ animationDelay: '0.5s' }}></div>
      <div className="absolute w-[600px] h-[600px] border border-orange-500/5 rounded-full animate-ping" style={{ animationDelay: '1s' }}></div>
      
      <div className="relative bg-gradient-to-br from-orange-400 to-red-500 p-6 rounded-full shadow-[0_0_50px_rgba(249,115,22,0.6)] mb-8">
        <HeartPulse size={56} className="text-white animate-pulse" />
      </div>

      <h2 className="text-2xl font-bold mb-2">正在呼叫周边英雄...</h2>
      <p className="text-gray-400 text-sm mb-12">已通知半径 5km 内的 18 位汪星人</p>

      <div className="bg-gray-800 px-6 py-3 rounded-full flex items-center border border-gray-700 shadow-inner">
        <div className="w-2 h-2 bg-green-400 rounded-full animate-pulse mr-3"></div>
        <span className="text-sm">有 3 位宠主正在查看您的求助</span>
      </div>
      
      <div className="absolute bottom-12 flex gap-4 w-full px-8 opacity-50 hover:opacity-100 transition-opacity">
        <button onClick={() => navigate('sos_success')} className="flex-1 bg-green-600/30 border border-green-500 text-green-400 py-2 rounded-lg text-xs">模拟匹配成功</button>
        <button onClick={() => navigate('sos_failed')} className="flex-1 bg-red-600/30 border border-red-500 text-red-400 py-2 rounded-lg text-xs">模拟无响应超时</button>
      </div>
      <button onClick={() => navigate('main')} className="absolute top-10 right-6 text-gray-500">取消</button>
    </div>
  );

  const SOSFailedView = () => (
    <div className="p-6 min-h-screen bg-slate-50 flex flex-col items-center justify-center">
      <div className="text-6xl mb-6 opacity-50 grayscale">🥺</div>
      <h2 className="text-2xl font-bold text-gray-800 mb-2">暂时无人响应</h2>
      <p className="text-gray-500 text-center text-sm mb-10 px-4">
        5公里内的英雄们可能正在忙碌。不要灰心，我们可以扩大搜索范围，或联系专业机构。
      </p>

      <div className="w-full space-y-4">
        <button onClick={() => navigate('sos_radar')} className="w-full bg-orange-500 text-white font-bold py-4 rounded-xl shadow-lg shadow-orange-200">
          扩大至全城范围重试 (15km)
        </button>
        <button className="w-full bg-white border border-gray-200 text-gray-700 font-bold py-4 rounded-xl flex items-center justify-center">
          <Phone size={18} className="mr-2 text-teal-600" /> 联系官方中心血库
        </button>
      </div>
      <button onClick={() => navigate('main')} className="mt-8 text-gray-400 text-sm underline">取消求助</button>
    </div>
  );

  const SOSSuccessView = () => (
    <div className="p-6 min-h-screen bg-green-50 flex flex-col items-center pt-20">
      <div className="text-7xl mb-6 bg-white p-6 rounded-full shadow-2xl shadow-green-200/50 animate-bounce">
        🤝
      </div>
      <h2 className="text-3xl font-black text-gray-800 mb-2 tracking-tight">匹配成功！</h2>
      <p className="text-green-600 font-bold mb-10">英雄正在赶来的路上</p>

      <div className="bg-white w-full rounded-3xl p-6 shadow-xl shadow-gray-100 border border-green-100 relative">
        <div className="absolute -top-4 left-1/2 transform -translate-x-1/2 bg-gradient-to-r from-green-400 to-emerald-500 text-white px-6 py-1.5 rounded-full text-xs font-bold shadow-md">
          接单志愿者
        </div>
        
        <div className="flex items-center mb-6 mt-4">
          <div className="w-16 h-16 bg-yellow-100 border-2 border-yellow-300 rounded-full flex items-center justify-center text-3xl mr-4 shadow-inner relative">
            🦮<div className="absolute -bottom-1 -right-1 bg-green-500 p-1 rounded-full text-white border-2 border-white"><Shield size={10}/></div>
          </div>
          <div>
            <h3 className="text-xl font-bold text-gray-800">Max (金毛)</h3>
            <p className="text-sm text-gray-500 mt-1">血型: DEA 1.1 阳性 | 体重: 28kg</p>
            <div className="flex gap-1 mt-2">
              <span className="bg-blue-50 text-blue-600 text-[10px] px-2 py-0.5 rounded">救护老手 (6次)</span>
            </div>
          </div>
        </div>

        <button onClick={() => navigate('sos_tracking')} className="w-full bg-green-500 text-white py-4 rounded-2xl font-bold flex items-center justify-center shadow-[0_8px_20px_rgba(34,197,94,0.3)] active:scale-95 transition-transform">
          查看实时位置与进度
        </button>
      </div>
    </div>
  );

  const SOSTrackingView = () => (
    <div className="min-h-screen bg-gray-100 flex flex-col relative">
      <div className="flex-1 bg-blue-50/50 relative overflow-hidden flex items-center justify-center border-b border-gray-200">
        <Map size={120} className="text-blue-100 absolute opacity-50" />
        <div className="w-full h-full border-[10px] border-blue-50 relative">
           <svg className="absolute w-full h-full text-blue-300" strokeWidth="4" fill="none">
             <path d="M 50 100 Q 150 150 250 300" stroke="currentColor" strokeDasharray="5,5" className="animate-pulse" />
           </svg>
           <div className="absolute top-20 left-[40px] bg-white p-2 rounded-full shadow-lg z-10 text-xl">🦮</div>
           <div className="absolute bottom-20 right-[100px] bg-orange-500 p-2 rounded-full shadow-lg z-10 text-white"><MapPin size={20}/></div>
        </div>
        <button onClick={() => navigate('main')} className="absolute top-12 left-4 bg-white p-3 rounded-full shadow-md text-gray-600">
          <ChevronLeft size={24} />
        </button>
      </div>

      <div className="bg-white rounded-t-3xl p-6 -mt-6 z-20 shadow-[0_-10px_30px_rgba(0,0,0,0.05)]">
        <div className="w-12 h-1.5 bg-gray-200 rounded-full mx-auto mb-6"></div>
        <div className="flex justify-between items-center mb-6">
          <div>
            <h2 className="text-2xl font-bold text-gray-800">预计 12 分钟 后到达</h2>
            <p className="text-sm text-gray-500 mt-1">剩余距离 3.2 km · 交通顺畅</p>
          </div>
          <div className="w-14 h-14 bg-green-50 rounded-full flex items-center justify-center">
            <Navigation className="text-green-500" size={28} />
          </div>
        </div>

        <div className="bg-gray-50 rounded-2xl p-4 flex items-center justify-between">
          <div className="flex items-center">
            <div className="w-12 h-12 bg-gray-200 rounded-full mr-3 border-2 border-white shadow-sm flex items-center justify-center">👨</div>
            <div>
              <p className="font-bold text-gray-800 text-sm">王先生 (Max家长)</p>
              <p className="text-xs text-gray-500 flex items-center"><Star size={10} className="text-yellow-400 mr-0.5 fill-current"/> 5.0 好心人</p>
            </div>
          </div>
          <div className="flex gap-2">
            <button className="w-10 h-10 bg-white rounded-full flex items-center justify-center shadow-sm text-gray-600 border border-gray-100"><MessageCircle size={20}/></button>
            <button className="w-10 h-10 bg-green-500 rounded-full flex items-center justify-center shadow-md text-white"><Phone size={20}/></button>
          </div>
        </div>
      </div>
    </div>
  );

  const DonorNavView = () => (
    <div className="min-h-screen bg-white flex flex-col">
      <TopBar title="前往医院" onBack={() => navigate('main')} />
      <div className="flex-1 bg-gray-200 relative flex items-center justify-center">
        <Map size={80} className="text-gray-400 opacity-30" />
        <div className="absolute bottom-6 left-1/2 -translate-x-1/2 bg-blue-600 text-white px-6 py-3 rounded-full font-bold shadow-lg flex items-center gap-2">
          <Navigation size={20} /> 导航中... 3.2km
        </div>
      </div>
      <div className="p-6 bg-white shadow-[0_-10px_20px_rgba(0,0,0,0.05)] rounded-t-3xl -mt-4 relative z-10">
        <h3 className="font-bold text-gray-800 text-lg mb-1">瑞鹏宠物医院 (南山中心店)</h3>
        <p className="text-gray-500 text-sm mb-6 flex items-center"><MapPin size={14} className="mr-1"/> 深南大道9001号</p>
        <div className="flex gap-3">
          <button className="flex-1 bg-gray-100 text-gray-700 py-3 rounded-xl font-bold flex justify-center items-center">
            <Phone size={18} className="mr-2" /> 联系求助者
          </button>
          <button onClick={() => navigate('donor_verify')} className="flex-1 bg-teal-500 text-white py-3 rounded-xl font-bold shadow-lg shadow-teal-200">
            我已到达
          </button>
        </div>
      </div>
    </div>
  );

  const DonorVerifyView = () => (
    <div className="min-h-screen bg-teal-500 flex flex-col items-center justify-center p-6 text-white text-center">
      <h2 className="text-2xl font-bold mb-8">出示给主治医生核销</h2>
      <div className="bg-white p-8 rounded-3xl shadow-2xl relative">
        <div className="w-48 h-48 bg-gray-100 mx-auto flex items-center justify-center rounded-xl border-4 border-dashed border-gray-300 mb-6 relative overflow-hidden">
          <QrCode size={120} className="text-gray-800" />
          <div className="absolute top-0 left-0 w-full h-1 bg-teal-400 shadow-[0_0_10px_rgba(45,212,191,0.8)] animate-[scan_2s_ease-in-out_infinite]"></div>
        </div>
        <h3 className="text-xl font-bold text-gray-800 mb-2">奥利奥 (献血者)</h3>
        <p className="text-gray-500 text-sm mb-6">核销码: 8492-4011</p>
        <button onClick={() => navigate('donor_reward')} className="w-full bg-teal-50 text-teal-600 font-bold py-3 rounded-xl border border-teal-100">
          (演示) 模拟医生扫码成功
        </button>
      </div>
      <p className="mt-8 text-teal-100 text-sm">核销后，系统将记录本次荣誉并为您生成免费体检报告</p>
    </div>
  );

  const DonorRewardView = () => (
    <div className="min-h-screen bg-slate-900 flex flex-col items-center justify-center p-6 relative overflow-hidden">
      <div className="absolute inset-0 bg-[url('https://www.transparenttextures.com/patterns/stardust.png')] opacity-30"></div>
      <div className="text-8xl mb-4 relative z-10 animate-bounce">🦸‍♂️</div>
      <h2 className="text-4xl font-black text-white mb-2 tracking-widest relative z-10">致敬英雄</h2>
      <p className="text-yellow-400 font-bold mb-10 text-lg relative z-10">你和奥利奥拯救了一个生命！</p>

      <div className="bg-gradient-to-b from-gray-800 to-gray-900 w-full rounded-3xl p-8 border border-gray-700 shadow-2xl relative z-10">
        <div className="flex justify-between items-center mb-8">
           <div className="text-center">
             <p className="text-gray-400 text-xs mb-1">获得生命积分</p>
             <p className="text-2xl font-bold text-teal-400">+500</p>
           </div>
           <div className="w-px h-10 bg-gray-700"></div>
           <div className="text-center">
             <p className="text-gray-400 text-xs mb-1">获得免费体检</p>
             <p className="text-2xl font-bold text-teal-400">1次</p>
           </div>
        </div>
        <div className="bg-gray-800 rounded-2xl p-4 flex items-center justify-between border border-gray-700 mb-8">
          <div className="flex items-center">
            <div className="w-12 h-12 bg-yellow-900/50 rounded-full flex items-center justify-center mr-3 border border-yellow-700/50">
              <Award size={24} className="text-yellow-500" />
            </div>
            <div>
              <p className="font-bold text-white text-sm">解锁新成就徽章</p>
              <p className="text-xs text-yellow-500">『中级生命卫士』</p>
            </div>
          </div>
        </div>
        <button onClick={() => navigate('profile')} className="w-full bg-gradient-to-r from-teal-500 to-emerald-500 text-white font-bold py-4 rounded-xl shadow-lg shadow-teal-500/30 flex items-center justify-center">
          <Share2 size={20} className="mr-2" /> 生成我的英雄海报
        </button>
        <button onClick={() => navigate('main')} className="w-full mt-4 text-gray-400 font-bold py-2">返回首页</button>
      </div>
    </div>
  );

  const MedicalReportsView = () => (
    <div className="min-h-screen bg-slate-50">
      <TopBar title="体检档案库" onBack={() => navigate('main')} />
      <div className="p-4 space-y-4">
        {[
          { date: '2023-10-15', type: '献血前全套生化 (福利)', status: '全优' },
          { date: '2023-05-20', type: '献血前血常规 (福利)', status: '正常' },
          { date: '2022-12-01', type: '年度常规体检', status: '正常' }
        ].map((report, i) => (
          <div key={i} onClick={() => navigate('report_detail')} className="bg-white p-4 rounded-xl shadow-sm flex justify-between items-center cursor-pointer active:scale-95 transition-transform">
            <div className="flex items-center">
              <div className="w-10 h-10 bg-blue-50 rounded-full flex items-center justify-center mr-3 text-blue-500"><FileText size={20}/></div>
              <div>
                <p className="text-sm font-bold text-gray-800">{report.type}</p>
                <p className="text-xs text-gray-400 mt-1">{report.date}</p>
              </div>
            </div>
            <div className="flex items-center">
              <span className="text-xs text-green-600 bg-green-50 px-2 py-1 rounded mr-2">{report.status}</span>
              <ChevronRight size={16} className="text-gray-300" />
            </div>
          </div>
        ))}
      </div>
    </div>
  );

  const ReportDetailView = () => (
    <div className="min-h-screen bg-white">
      <TopBar title="检测报告详情" onBack={() => navigate('medical_reports')} />
      <div className="p-6">
        <h2 className="text-xl font-bold text-gray-800 mb-1">全套生化与血常规</h2>
        <p className="text-sm text-gray-500 mb-6 border-b border-gray-100 pb-4">出具机构: 瑞鹏宠物(南山) · 2023-10-15</p>
        
        <div className="mb-6 bg-green-50 p-4 rounded-xl text-green-800 text-sm font-bold flex items-start">
          <CheckCircle size={20} className="mr-2 flex-shrink-0" />
          医生解读：奥利奥各项指标均在完美健康区间，造血功能极佳，非常适合作为献血志愿者。
        </div>

        <h3 className="font-bold text-gray-800 mb-4">核心指标 (红细胞系)</h3>
        <div className="space-y-6">
          <div>
            <div className="flex justify-between text-sm mb-2">
              <span className="font-bold text-gray-700">RBC (红细胞计数)</span>
              <span className="font-bold text-gray-800">6.8 <span className="text-xs text-gray-400 font-normal">M/μL</span></span>
            </div>
            <div className="h-2 w-full bg-gray-100 rounded-full relative">
              <div className="absolute top-0 left-0 h-full bg-teal-500 rounded-full" style={{width: '60%'}}></div>
              <div className="absolute top-0 left-[40%] w-[40%] h-full bg-teal-500/20 rounded-full border-x border-teal-500"></div>
            </div>
            <p className="text-[10px] text-gray-400 mt-1 text-right">参考值: 5.5 - 8.5</p>
          </div>
          <div>
            <div className="flex justify-between text-sm mb-2">
              <span className="font-bold text-gray-700">HGB (血红蛋白)</span>
              <span className="font-bold text-gray-800">152 <span className="text-xs text-gray-400 font-normal">g/L</span></span>
            </div>
            <div className="h-2 w-full bg-gray-100 rounded-full relative">
              <div className="absolute top-0 left-0 h-full bg-teal-500 rounded-full" style={{width: '70%'}}></div>
              <div className="absolute top-0 left-[50%] w-[35%] h-full bg-teal-500/20 rounded-full border-x border-teal-500"></div>
            </div>
            <p className="text-[10px] text-gray-400 mt-1 text-right">参考值: 120 - 180</p>
          </div>
        </div>
        <button className="w-full mt-10 bg-gray-50 text-gray-600 font-bold py-4 rounded-xl border border-gray-200">下载 PDF 原件</button>
      </div>
    </div>
  );

  const HistoryView = () => (
    <div className="min-h-screen bg-slate-50 pb-10">
      <TopBar title="生命接力足迹" onBack={() => navigate('main')} />
      <div className="p-6 relative">
        <div className="absolute left-9 top-10 bottom-10 w-0.5 bg-gray-200"></div>
        <div className="space-y-8 relative z-10">
          <div className="flex">
            <div className="w-6 h-6 bg-red-500 rounded-full border-4 border-white shadow-sm flex-shrink-0 mt-1"></div>
            <div className="ml-4 bg-white p-4 rounded-xl shadow-sm flex-1 border border-gray-100">
              <p className="text-xs text-gray-400 mb-1">2023年10月2日</p>
              <h4 className="font-bold text-gray-800 mb-1">成功捐献 200ml 血液</h4>
              <p className="text-sm text-gray-600">救助了一只因为车祸大出血的哈士奇。你是一个伟大的英雄！</p>
              <div className="mt-3 bg-red-50 text-red-600 text-xs px-2 py-1 inline-block rounded font-bold">+500 积分</div>
            </div>
          </div>
          <div className="flex">
            <div className="w-6 h-6 bg-teal-500 rounded-full border-4 border-white shadow-sm flex-shrink-0 mt-1"></div>
            <div className="ml-4 bg-white p-4 rounded-xl shadow-sm flex-1 border border-gray-100">
              <p className="text-xs text-gray-400 mb-1">2023年5月10日</p>
              <h4 className="font-bold text-gray-800 mb-1">加入 PawsLife 互助库</h4>
              <p className="text-sm text-gray-600">完成首次血型检测，成为光荣的预备役。</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  );

  const SettingsView = () => (
    <div className="min-h-screen bg-slate-50">
      <TopBar title="设置" onBack={() => navigate('main')} />
      <div className="p-4 space-y-6 mt-2">
        <div className="bg-white rounded-2xl overflow-hidden border border-gray-100">
          <div className="flex justify-between items-center p-4 border-b border-gray-50">
            <span className="text-sm font-bold text-gray-700">接收紧急求助推送 (短信+弹窗)</span>
            <div className="w-12 h-6 bg-teal-500 rounded-full relative"><div className="w-5 h-5 bg-white rounded-full absolute right-0.5 top-0.5 shadow"></div></div>
          </div>
          <div className="flex justify-between items-center p-4">
            <span className="text-sm font-bold text-gray-700">允许在排行榜展示我</span>
            <div className="w-12 h-6 bg-teal-500 rounded-full relative"><div className="w-5 h-5 bg-white rounded-full absolute right-0.5 top-0.5 shadow"></div></div>
          </div>
        </div>
        <div className="bg-white rounded-2xl overflow-hidden border border-gray-100">
          <div className="flex justify-between items-center p-4 border-b border-gray-50 text-sm font-bold text-gray-700"><span>账号与安全</span> <ChevronRight size={16} className="text-gray-400"/></div>
          <div className="flex justify-between items-center p-4 border-b border-gray-50 text-sm font-bold text-gray-700"><span>隐私政策</span> <ChevronRight size={16} className="text-gray-400"/></div>
          <div className="flex justify-between items-center p-4 text-sm font-bold text-gray-700"><span>关于 PawsLife (v1.0.0)</span> <ChevronRight size={16} className="text-gray-400"/></div>
        </div>
        <button onClick={() => navigate('login')} className="w-full bg-white text-red-500 font-bold py-4 rounded-2xl border border-red-100 mt-8">
          退出登录
        </button>
      </div>
    </div>
  );

  const SplashView = () => {
    useEffect(() => {
      const timer = setTimeout(() => navigate('onboarding'), 2000);
      return () => clearTimeout(timer);
    }, []);

    return (
      <motion.div 
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        exit={{ opacity: 0 }}
        className="min-h-screen bg-teal-500 flex flex-col items-center justify-center text-white"
      >
        <motion.div 
          initial={{ scale: 0.5, rotate: -20 }}
          animate={{ scale: 1, rotate: 0 }}
          transition={{ type: "spring", stiffness: 260, damping: 20 }}
          className="bg-white p-6 rounded-3xl shadow-2xl mb-6"
        >
          <HeartPulse size={64} className="text-teal-500 animate-pulse" />
        </motion.div>
        <motion.h1 
          initial={{ y: 20, opacity: 0 }}
          animate={{ y: 0, opacity: 1 }}
          transition={{ delay: 0.3 }}
          className="text-4xl font-black tracking-wider mb-2"
        >
          PawsLife
        </motion.h1>
        <motion.p 
          initial={{ opacity: 0 }}
          animate={{ opacity: 1 }}
          transition={{ delay: 0.6 }}
          className="text-teal-100 tracking-widest text-sm"
        >
          连接每一次心跳
        </motion.p>
      </motion.div>
    );
  };

  const OnboardingView = () => {
    const [step, setStep] = useState(0);

    const slides = [
      {
        title: "生命接力 · 互助救援",
        desc: "我们的目标是帮助急需输血的患病毛孩，及时获得安全有效的生命救援。",
        visual: (
          <div className="relative w-56 h-56 flex items-center justify-center">
            <div className="absolute inset-0 bg-red-50 rounded-[40px] rotate-6"></div>
            <div className="absolute inset-0 bg-red-100 rounded-[40px] -rotate-3 opacity-50"></div>
            <HeartPulse size={90} className="text-red-500 z-10 animate-pulse" />
            <div className="absolute top-4 right-4 bg-white rounded-full p-2 shadow-sm text-2xl z-20">🩸</div>
            <div className="absolute -bottom-4 -left-2 text-6xl bg-white rounded-full p-2 shadow-lg z-20 border-4 border-red-50">🐶</div>
          </div>
        )
      },
      {
        title: "安全精准 · 高效匹配",
        desc: "提供更专业、更安全的血型库。一键呼叫，智能匹配周边符合条件的健康血源。",
        visual: (
          <div className="relative w-56 h-56 flex items-center justify-center">
            <div className="absolute inset-0 bg-teal-50 rounded-full scale-105"></div>
            <div className="absolute inset-4 border-2 border-dashed border-teal-200 rounded-full animate-[spin_10s_linear_infinite]"></div>
            <Search size={80} className="text-teal-500 z-10" />
            <div className="absolute -top-2 left-8 bg-white rounded-full p-3 shadow-md z-20 text-xl border-2 border-teal-50">🏥</div>
            <div className="absolute bottom-2 right-4 bg-white rounded-full p-3 shadow-md z-20 text-3xl border-2 border-teal-50">📱</div>
          </div>
        )
      },
      {
        title: "你和毛孩 · 都是英雄",
        desc: "宠物不是商品，它是陪伴我们的超级英雄。每一次挺身而出，都是在延续另一个奇迹。",
        visual: (
          <div className="relative w-56 h-56 flex items-center justify-center">
            <div className="absolute inset-0 bg-yellow-50 rounded-bl-[60px] rounded-tr-[60px] rounded-tl-2xl rounded-br-2xl"></div>
            <Award size={100} className="text-yellow-500 z-10 drop-shadow-lg" />
            <div className="absolute top-0 right-2 bg-white rounded-full p-2 shadow-md z-20 text-2xl border-2 border-yellow-100">🐾</div>
            <div className="absolute -bottom-4 left-6 bg-white rounded-full p-2 shadow-xl z-20 text-5xl border-4 border-yellow-50">🦸‍♂️</div>
          </div>
        )
      }
    ];

    const handleNext = () => {
      if (step < 2) setStep(step + 1);
      else navigate('login');
    };

    return (
      <motion.div 
        initial={{ opacity: 0, x: 20 }}
        animate={{ opacity: 1, x: 0 }}
        exit={{ opacity: 0, x: -20 }}
        className="min-h-screen bg-white flex flex-col justify-between pb-10 pt-12"
      >
        <div className="w-full flex justify-end px-6">
          <button onClick={() => navigate('login')} className="text-xs text-gray-400 border border-gray-200 px-4 py-1.5 rounded-full hover:bg-gray-50 transition-colors">
            跳过
          </button>
        </div>

        <div className="flex-1 flex flex-col items-center justify-center px-8 w-full mt-4">
          <AnimatePresence mode="wait">
            <motion.div 
              key={step}
              initial={{ opacity: 0, scale: 0.9 }}
              animate={{ opacity: 1, scale: 1 }}
              exit={{ opacity: 0, scale: 1.1 }}
              className="h-72 flex items-center justify-center mb-10 w-full"
            >
              {slides[step].visual}
            </motion.div>
          </AnimatePresence>

          <div className="flex gap-2 mb-10">
            {slides.map((_, i) => (
              <div key={i} className={`h-1.5 rounded-full transition-all duration-300 ${i === step ? 'w-8 bg-teal-500' : 'w-2 bg-gray-200'}`} />
            ))}
          </div>

          <div className="text-center w-full px-2">
            <motion.h2 
              key={`title-${step}`}
              initial={{ opacity: 0, y: 10 }}
              animate={{ opacity: 1, y: 0 }}
              className="text-2xl font-black text-gray-800 mb-4"
            >
              {slides[step].title}
            </motion.h2>
            <motion.p 
              key={`desc-${step}`}
              initial={{ opacity: 0, y: 10 }}
              animate={{ opacity: 1, y: 0 }}
              transition={{ delay: 0.1 }}
              className="text-sm text-gray-500 leading-relaxed h-16"
            >
              {slides[step].desc}
            </motion.p>
          </div>
        </div>

        <div className="w-full px-8 h-16 flex items-center justify-center mt-6">
          <motion.button 
            whileTap={{ scale: 0.95 }}
            onClick={handleNext} 
            className={`${step < 2 ? 'w-16 h-16 rounded-full' : 'w-full rounded-2xl py-4'} bg-teal-500 text-white font-bold flex items-center justify-center shadow-lg shadow-teal-200 transition-all duration-300`}
          >
            {step < 2 ? <ChevronRight size={32} /> : "立即开启"}
          </motion.button>
        </div>
      </motion.div>
    );
  };

  const LoginView = () => (
    <motion.div 
      initial={{ opacity: 0, y: 20 }}
      animate={{ opacity: 1, y: 0 }}
      className="min-h-screen bg-white p-8 flex flex-col justify-center"
    >
      <div className="w-16 h-16 bg-teal-100 text-teal-600 rounded-2xl flex items-center justify-center mb-8">
        <Shield size={32} />
      </div>
      <h1 className="text-3xl font-bold text-gray-800 mb-2">欢迎加入</h1>
      <p className="text-gray-500 mb-10">为了毛孩的健康，请验证您的手机号</p>
      
      <div className="space-y-4 mb-8">
        <div className="flex items-center bg-gray-50 rounded-2xl p-4 border border-gray-100">
          <span className="text-gray-500 font-bold mr-3 border-r border-gray-200 pr-3">+86</span>
          <input type="tel" placeholder="输入手机号" className="bg-transparent w-full outline-none text-gray-800" />
        </div>
        <div className="flex items-center gap-4">
          <div className="flex-1 bg-gray-50 rounded-2xl p-4 border border-gray-100">
            <input type="number" placeholder="验证码" className="bg-transparent w-full outline-none text-gray-800" />
          </div>
          <button className="text-teal-600 font-bold px-4">获取</button>
        </div>
      </div>
      
      <motion.button 
        whileTap={{ scale: 0.98 }}
        onClick={() => navigate('pet_reg_1')} 
        className="w-full bg-teal-500 text-white font-bold py-4 rounded-2xl shadow-lg shadow-teal-200 mb-6"
      >
        登录 / 注册
      </motion.button>
      <p className="text-center text-xs text-gray-400">登录即代表同意《用户协议》与《隐私政策》</p>
    </motion.div>
  );

  const PetRegBasicView = () => (
    <div className="min-h-screen bg-slate-50">
      <TopBar title="添加毛孩档案 (1/2)" onBack={() => navigate('login')} />
      <div className="p-6">
        <div className="flex justify-center mb-8 mt-4">
          <div className="w-24 h-24 bg-gray-200 rounded-full flex items-center justify-center text-gray-400 relative">
            <Camera size={32} />
            <div className="absolute bottom-0 right-0 bg-teal-500 p-2 rounded-full text-white border-2 border-white"><CheckCircle size={16}/></div>
          </div>
        </div>
        <div className="space-y-4 mb-8">
          <div>
            <label className="text-sm font-bold text-gray-700 block mb-2">毛孩昵称</label>
            <input type="text" placeholder="例如：奥利奥" className="w-full bg-white p-4 rounded-xl border border-gray-200 outline-none" />
          </div>
          <div>
            <label className="text-sm font-bold text-gray-700 block mb-2">种类</label>
            <div className="flex gap-4">
              <button className="flex-1 py-3 bg-teal-50 border-2 border-teal-500 text-teal-700 font-bold rounded-xl">狗狗 🐶</button>
              <button className="flex-1 py-3 bg-white border border-gray-200 text-gray-500 font-bold rounded-xl">猫咪 🐱</button>
            </div>
          </div>
          <div>
            <label className="text-sm font-bold text-gray-700 block mb-2">品种</label>
            <input type="text" placeholder="例如：边境牧羊犬" className="w-full bg-white p-4 rounded-xl border border-gray-200 outline-none" />
          </div>
        </div>
        <button onClick={() => navigate('pet_reg_2')} className="w-full bg-teal-500 text-white font-bold py-4 rounded-xl shadow-lg shadow-teal-200">
          下一步
        </button>
      </div>
    </div>
  );

  const PetRegMedicalView = () => (
    <div className="min-h-screen bg-slate-50">
      <TopBar title="添加毛孩档案 (2/2)" onBack={() => navigate('pet_reg_1')} />
      <div className="p-6">
        <div className="bg-blue-50 text-blue-700 p-4 rounded-xl text-sm flex items-start mb-6">
          <AlertCircle size={20} className="mr-2 flex-shrink-0 mt-0.5" />
          <p>完善医疗信息有助于在紧急时刻快速匹配血源。不知道血型？没关系，可选择“未测”。</p>
        </div>
        <div className="space-y-4 mb-8">
          <div>
            <label className="text-sm font-bold text-gray-700 block mb-2">血型 (狗狗)</label>
            <select className="w-full bg-white p-4 rounded-xl border border-gray-200 outline-none text-gray-700">
              <option>未测 / 不知道</option>
              <option>DEA 1.1 阳性 (+)</option>
              <option>DEA 1.1 阴性 (-)</option>
            </select>
          </div>
          <div>
            <label className="text-sm font-bold text-gray-700 block mb-2">体重 (kg) - 影响能否献血</label>
            <input type="number" placeholder="例如：15" className="w-full bg-white p-4 rounded-xl border border-gray-200 outline-none" />
          </div>
          <div className="flex items-center justify-between bg-white p-4 rounded-xl border border-gray-200 mt-6">
            <div>
              <p className="font-bold text-gray-800">加入互助志愿者</p>
              <p className="text-xs text-gray-500">在他人危急时，愿意收到献血求助</p>
            </div>
            <div className="w-12 h-6 bg-teal-500 rounded-full relative transition-colors cursor-pointer">
              <div className="w-5 h-5 bg-white rounded-full absolute right-0.5 top-0.5 shadow"></div>
            </div>
          </div>
        </div>
        <button onClick={() => navigate('main')} className="w-full bg-teal-500 text-white font-bold py-4 rounded-xl shadow-lg shadow-teal-200">
          完成并进入首页
        </button>
      </div>
    </div>
  );

  const HomeView = () => (
    <div className="p-6 pb-24 bg-slate-50 min-h-screen">
      <header className="flex justify-between items-center mb-6 pt-2">
        <div>
          <h1 className="text-2xl font-bold text-gray-800 flex items-center">
            你好, 奥利奥家长 <div className="ml-2 bg-yellow-100 text-yellow-600 text-xs px-2 py-0.5 rounded-full font-bold">LV.3</div>
          </h1>
          <p className="text-sm text-gray-500 mt-1 flex items-center"><MapPin size={12} className="mr-1"/> 深圳市 · 南山区</p>
        </div>
        <button onClick={() => navigate('notifications')} className="bg-white p-2.5 rounded-full shadow-sm relative">
          <Bell size={22} className="text-gray-600" />
          <span className="absolute top-2 right-2.5 w-2 h-2 bg-red-500 rounded-full border-2 border-white"></span>
        </button>
      </header>

      <motion.div 
        whileHover={{ scale: 1.02 }}
        className="bg-blue-600 rounded-2xl p-4 mb-6 text-white flex justify-between items-center shadow-lg shadow-blue-200"
      >
        <div>
          <p className="font-bold text-sm mb-1">🔍 体验献血者接单流程？</p>
          <p className="text-xs text-blue-200">点击右侧按钮模拟收到附近紧急求助</p>
        </div>
        <button onClick={() => navigate('donor_alert')} className="bg-white text-blue-600 px-3 py-2 rounded-xl text-sm font-bold whitespace-nowrap">
          模拟接单
        </button>
      </motion.div>

      <motion.div 
        whileTap={{ scale: 0.98 }}
        onClick={() => navigate('leaderboard')} 
        className="bg-gradient-to-br from-teal-400 to-emerald-500 rounded-3xl p-6 text-white shadow-lg shadow-teal-200/50 mb-8 relative overflow-hidden"
      >
        <HeartPulse className="absolute -right-4 -bottom-4 text-white opacity-10" size={120} />
        <div className="relative z-10 flex justify-between items-center">
          <div>
            <p className="text-teal-50 text-sm mb-1 flex items-center">本月城市献血播报 <ChevronRight size={14}/></p>
            <h2 className="text-3xl font-black font-mono mt-1">128<span className="text-sm font-normal opacity-90 ml-2 tracking-wide">次生命接力</span></h2>
          </div>
        </div>
      </motion.div>

      <div className="flex justify-between items-end mb-4">
        <h3 className="font-bold text-lg text-gray-800">附近急救 (1)</h3>
        <span className="text-xs text-teal-600 font-bold">查看全部</span>
      </div>
      
      <div className="bg-white rounded-2xl p-4 shadow-sm border border-orange-100 mb-8">
        <div className="flex items-start">
          <div className="bg-orange-100 p-3 rounded-2xl mr-4 mt-1">
            <AlertCircle size={24} className="text-orange-600" />
          </div>
          <div className="flex-1">
            <div className="flex justify-between items-start">
              <h4 className="font-bold text-gray-800 text-lg">急求 DEA 1.1 阴性血</h4>
              <span className="bg-red-50 text-red-500 text-xs px-2 py-1 rounded font-bold">极度紧急</span>
            </div>
            <p className="text-sm text-gray-600 mt-1">金毛 / 3岁 / 贫血急救</p>
            <p className="text-xs text-gray-400 mt-2 flex items-center">
              <MapPin size={12} className="mr-1" /> 瑞鹏宠物医院 (3.2km)
            </p>
          </div>
        </div>
        <div className="mt-4 pt-4 border-t border-gray-50 flex gap-3">
          <button className="flex-1 bg-orange-50 text-orange-600 py-2.5 rounded-xl text-sm font-bold">转发扩散</button>
          <button onClick={() => navigate('donor_alert')} className="flex-1 bg-orange-500 text-white py-2.5 rounded-xl text-sm font-bold shadow-md shadow-orange-200">立即响应</button>
        </div>
      </div>

      <div className="flex justify-between items-end mb-4">
        <h3 className="font-bold text-lg text-gray-800">献血与健康</h3>
      </div>
      <div className="grid grid-cols-2 gap-4">
        <div onClick={() => navigate('article')} className="bg-white p-4 rounded-2xl shadow-sm border border-gray-50 active:scale-95 transition-transform cursor-pointer">
          <div className="w-10 h-10 bg-red-50 rounded-full flex items-center justify-center text-red-500 mb-3"><Droplet size={20}/></div>
          <h4 className="font-bold text-sm text-gray-800">宠物血型全指南</h4>
          <p className="text-xs text-gray-400 mt-1 line-clamp-1">A型、B型还是AB型？</p>
        </div>
        <div onClick={() => navigate('report_detail')} className="bg-white p-4 rounded-2xl shadow-sm border border-gray-50 active:scale-95 transition-transform cursor-pointer">
          <div className="w-10 h-10 bg-blue-50 rounded-full flex items-center justify-center text-blue-500 mb-3"><Activity size={20}/></div>
          <h4 className="font-bold text-sm text-gray-800">读懂血检报告</h4>
          <p className="text-xs text-gray-400 mt-1 line-clamp-1">RBC/HGB指标分析</p>
        </div>
      </div>
    </div>
  );

  const ProfileView = () => (
    <div className="min-h-screen bg-slate-50 pb-24">
      <div className="bg-teal-600 rounded-b-[40px] p-6 pt-10 text-white pb-14 relative shadow-lg">
        <div className="flex justify-between items-start mb-6">
          <h1 className="text-xl font-bold">我的档案</h1>
          <button onClick={() => navigate('settings')} className="p-2 hover:bg-teal-500 rounded-full transition-colors"><Settings size={22} /></button>
        </div>
        <div className="flex items-center">
          <div className="w-20 h-20 bg-white rounded-full flex items-center justify-center text-4xl mr-4 border-4 border-teal-400 shadow-inner">
            {petProfile.avatar}
          </div>
          <div>
            <h2 className="text-2xl font-bold flex items-center">{petProfile.name} <div className="ml-2 w-2 h-2 rounded-full bg-green-400 border border-white"></div></h2>
            <p className="text-teal-100 text-sm mt-1">{petProfile.breed} · 2岁</p>
          </div>
        </div>
        <div className="absolute -bottom-8 left-6 right-6 bg-white rounded-2xl p-5 shadow-md flex justify-around text-center text-gray-800">
          <div>
            <p className="text-xs text-gray-400 mb-1">血型</p>
            <p className="font-bold text-red-500">{petProfile.bloodType}</p>
          </div>
          <div className="w-px bg-gray-100"></div>
          <div onClick={() => navigate('history')} className="cursor-pointer active:scale-95">
            <p className="text-xs text-gray-400 mb-1">生命接力(次) <ChevronRight size={10} className="inline"/></p>
            <p className="font-bold text-teal-600 text-xl">{petProfile.donations}</p>
          </div>
          <div className="w-px bg-gray-100"></div>
          <div>
            <p className="text-xs text-gray-400 mb-1">爱心积分</p>
            <p className="font-bold text-orange-500 text-xl">{petProfile.points}</p>
          </div>
        </div>
      </div>

      <div className="p-6 mt-12">
        <h3 className="font-bold text-gray-800 mb-4 flex items-center">
          <Medal size={20} className="text-yellow-500 mr-2" /> 荣誉勋章库 (3)
        </h3>
        <div className="grid grid-cols-3 gap-3 mb-8">
          {petProfile.badges.map((badge, idx) => (
            <motion.div 
              key={idx} 
              whileHover={{ y: -5 }}
              className="bg-white p-3 rounded-2xl shadow-sm border border-gray-100 flex flex-col items-center text-center"
            >
              <div className="w-12 h-12 bg-gradient-to-br from-yellow-50 to-orange-50 rounded-full flex items-center justify-center text-2xl mb-2 shadow-inner">
                {idx === 0 ? '🚑' : idx === 1 ? '🦸‍♂️' : '💖'}
              </div>
              <span className="text-xs font-bold text-gray-700">{badge}</span>
            </motion.div>
          ))}
        </div>

        <div className="flex justify-between items-end mb-4">
          <h3 className="font-bold text-gray-800 flex items-center">
            <Activity size={20} className="text-blue-500 mr-2" /> 体检档案
          </h3>
          <span onClick={() => navigate('medical_reports')} className="text-xs text-teal-600 font-bold flex items-center cursor-pointer">查看全部 <ChevronRight size={14}/></span>
        </div>
        <div onClick={() => navigate('report_detail')} className="bg-white p-5 rounded-2xl shadow-sm border border-gray-100 cursor-pointer active:bg-gray-50">
          <div className="flex justify-between items-center mb-3">
            <span className="text-sm font-bold text-gray-700">最新生化全检 (献血福利)</span>
            <span className="text-[10px] text-green-600 bg-green-50 px-2 py-1 rounded font-bold border border-green-100">指标全优</span>
          </div>
          <p className="text-xs text-gray-400 mb-3">检测日期: 2023-10-15</p>
          <div className="flex gap-2">
            <div className="flex-1 bg-gray-50 p-2 rounded-lg text-center">
              <p className="text-[10px] text-gray-500">RBC</p>
              <p className="font-bold text-sm text-gray-800">6.8</p>
            </div>
            <div className="flex-1 bg-gray-50 p-2 rounded-lg text-center">
              <p className="text-[10px] text-gray-500">HGB</p>
              <p className="font-bold text-sm text-gray-800">152</p>
            </div>
            <div className="flex-1 bg-gray-50 p-2 rounded-lg text-center">
              <p className="text-[10px] text-gray-500">WBC</p>
              <p className="font-bold text-sm text-gray-800">10.5</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  );

  const SOSFormView = () => (
    <div className="p-6 min-h-screen bg-orange-50 pb-20">
      <header className="flex items-center mb-8 pt-4">
        <button onClick={() => navigate('main')} className="text-gray-500 p-2 bg-white rounded-full shadow-sm">
          <ChevronLeft size={24} />
        </button>
        <h1 className="text-xl font-bold text-gray-800 ml-4">发布紧急求助</h1>
      </header>

      <div className="bg-white rounded-3xl p-6 shadow-sm border border-orange-100">
        <div className="mb-6">
          <label className="block text-sm font-bold text-gray-700 mb-3">为哪只毛孩求助？</label>
          <div className="flex gap-4">
            <div className="flex-1 border-2 border-orange-500 bg-orange-50 rounded-2xl p-3 flex flex-col items-center relative overflow-hidden">
              <div className="absolute top-0 right-0 bg-orange-500 text-white text-[10px] px-2 py-1 rounded-bl-lg font-bold">我的档案</div>
              <div className="text-3xl mb-1">🐶</div>
              <span className="font-bold text-orange-700 text-sm">奥利奥</span>
            </div>
            <div className="flex-1 border-2 border-dashed border-gray-200 rounded-2xl p-3 flex flex-col items-center justify-center text-gray-400">
              <div className="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center mb-1">+</div>
              <span className="text-sm">其他毛孩</span>
            </div>
          </div>
        </div>

        <div className="mb-6">
          <label className="block text-sm font-bold text-gray-700 mb-2 flex justify-between">
            <span>所需血型</span> <span className="text-orange-500 font-normal">系统已自动带入</span>
          </label>
          <select className="w-full p-4 bg-orange-50/50 border border-orange-200 rounded-xl text-gray-800 focus:outline-none focus:border-orange-500 font-bold" defaultValue="DEA 1.1 阳性 (+)">
            <option>DEA 1.1 阳性 (+)</option>
            <option>DEA 1.1 阴性 (-)</option>
            <option>不确定，需到院配型</option>
          </select>
        </div>

        <div className="mb-8">
          <label className="block text-sm font-bold text-gray-700 mb-2">当前所在医院 (接头地点)</label>
          <div className="flex items-center p-4 bg-gray-50 border border-gray-200 rounded-xl">
            <MapPin size={20} className="text-orange-500 mr-2" />
            <input type="text" value="瑞鹏宠物医院 (南山中心店)" readOnly className="bg-transparent w-full text-gray-700 outline-none font-medium" />
            <ChevronRight size={20} className="text-gray-400"/>
          </div>
        </div>

        <motion.button 
          whileTap={{ scale: 0.95 }}
          onClick={() => navigate('sos_radar')} 
          className="w-full bg-orange-500 text-white font-bold text-lg py-4 rounded-2xl shadow-[0_8px_30px_rgba(249,115,22,0.3)] flex items-center justify-center"
        >
          <HeartPulse size={24} className="mr-2 animate-pulse" /> 发送 SOS 警报
        </motion.button>
      </div>
      <p className="text-center text-xs text-orange-400 mt-6 px-4 leading-relaxed">
        按下按钮后，系统将立即短信及弹窗通知半径 5km 内的 18 位符合条件的献血志愿者。
      </p>
    </div>
  );

  const DonorAlertView = () => (
    <motion.div 
      initial={{ opacity: 0, scale: 0.9 }}
      animate={{ opacity: 1, scale: 1 }}
      className="p-6 min-h-screen bg-red-600 flex flex-col justify-center text-white relative overflow-hidden"
    >
      <div className="absolute top-0 left-0 w-full h-full bg-[radial-gradient(circle,rgba(255,255,255,0.2)_0%,transparent_60%)] animate-pulse pointer-events-none"></div>
      
      <div className="text-center z-10 mb-8">
        <div className="bg-white/20 p-6 rounded-full inline-block mb-6 backdrop-blur-sm border border-white/30">
          <AlertCircle size={64} className="text-white animate-bounce" />
        </div>
        <h2 className="text-3xl font-black mb-2 tracking-wide">紧急求助响应</h2>
        <p className="text-red-100">距离您 3.2km 处有生命急需救援！</p>
      </div>

      <div className="bg-white rounded-3xl p-6 text-gray-800 z-10 shadow-2xl relative">
        <div className="absolute top-0 right-8 -translate-y-1/2 bg-red-500 text-white font-bold py-1 px-3 rounded-full text-xs shadow-md border-2 border-white">
          高度匹配: 98%
        </div>
        <h3 className="text-xl font-bold mb-4">需: DEA 1.1 阳性血</h3>
        <div className="flex gap-4 mb-6">
          <div className="bg-gray-50 rounded-xl p-3 flex-1">
            <p className="text-xs text-gray-500 mb-1">受助者</p>
            <p className="font-bold">金毛 / 3岁 / 贫血</p>
          </div>
          <div className="bg-gray-50 rounded-xl p-3 flex-1">
            <p className="text-xs text-gray-500 mb-1">接头医院</p>
            <p className="font-bold line-clamp-1">瑞鹏宠物(南山)</p>
          </div>
        </div>
        <div className="h-px bg-gray-100 w-full mb-6"></div>
        <p className="text-sm text-gray-600 mb-6 leading-relaxed">
          经核查，您的毛孩【奥利奥】符合献血条件（上次献血距今已超3个月）。预计前往医院需 15分钟，整个流程约 40分钟。
        </p>

        <div className="flex flex-col gap-3">
          <motion.button 
            whileTap={{ scale: 0.95 }}
            onClick={() => navigate('donor_nav')} 
            className="w-full bg-red-600 text-white font-bold text-lg py-4 rounded-2xl shadow-[0_8px_20px_rgba(220,38,38,0.4)] flex items-center justify-center relative overflow-hidden"
          >
            <HeartPulse size={20} className="mr-2" /> 确认接单，立即前往
          </motion.button>
          <button onClick={() => navigate('main')} className="w-full bg-gray-50 text-gray-500 font-bold py-4 rounded-2xl border border-gray-100">
            抱歉，当前不便
          </button>
        </div>
      </div>
    </motion.div>
  );

  // --- Main Shell ---
  const MainShell = () => (
    <div className="flex justify-center bg-gray-200 min-h-screen font-sans">
      <div className="w-full max-w-md bg-white relative shadow-2xl overflow-hidden">
        <AnimatePresence mode="wait">
          {currentTab === 'home' ? (
            <motion.div 
              key="home"
              initial={{ opacity: 0 }}
              animate={{ opacity: 1 }}
              exit={{ opacity: 0 }}
            >
              <HomeView />
            </motion.div>
          ) : (
            <motion.div 
              key="profile"
              initial={{ opacity: 0 }}
              animate={{ opacity: 1 }}
              exit={{ opacity: 0 }}
            >
              <ProfileView />
            </motion.div>
          )}
        </AnimatePresence>

        <div className="fixed bottom-0 w-full max-w-md bg-white border-t border-gray-100 flex justify-around py-2 pb-6 z-40 shadow-[0_-5px_20px_rgba(0,0,0,0.03)]">
          <button onClick={() => switchTab('home')} className={`flex flex-col items-center flex-1 py-1 ${currentTab === 'home' ? 'text-teal-600' : 'text-gray-400'}`}>
            <Home size={22} className={currentTab === 'home' ? 'fill-current opacity-20' : ''} />
            <span className="text-[10px] mt-1 font-medium">首页</span>
          </button>
          <div className="flex-1 flex justify-center">
            <motion.button 
              whileHover={{ scale: 1.1 }}
              whileTap={{ scale: 0.9 }}
              onClick={() => navigate('sos_form')} 
              className="flex flex-col items-center -mt-6"
            >
              <div className="bg-orange-500 text-white p-4 rounded-full shadow-xl shadow-orange-200 border-4 border-white">
                <HeartPulse size={28} />
              </div>
              <span className="text-[10px] mt-1 text-orange-600 font-bold">一键急救</span>
            </motion.button>
          </div>
          <button onClick={() => switchTab('profile')} className={`flex flex-col items-center flex-1 py-1 ${currentTab === 'profile' ? 'text-teal-600' : 'text-gray-400'}`}>
            <User size={22} className={currentTab === 'profile' ? 'fill-current opacity-20' : ''} />
            <span className="text-[10px] mt-1 font-medium">我的</span>
          </button>
        </div>
      </div>
    </div>
  );

  const renderView = () => {
    switch (currentView) {
      case 'splash': return <SplashView />;
      case 'onboarding': return <OnboardingView />;
      case 'login': return <LoginView />;
      case 'pet_reg_1': return <PetRegBasicView />;
      case 'pet_reg_2': return <PetRegMedicalView />;
      case 'notifications': return <NotificationsView />;
      case 'leaderboard': return <LeaderboardView />;
      case 'article': return <ArticleDetailView />;
      case 'sos_form': return <SOSFormView />;
      case 'sos_radar': return <SOSRadarView />;
      case 'sos_failed': return <SOSFailedView />;
      case 'sos_success': return <SOSSuccessView />;
      case 'sos_tracking': return <SOSTrackingView />;
      case 'donor_alert': return <DonorAlertView />;
      case 'donor_nav': return <DonorNavView />;
      case 'donor_verify': return <DonorVerifyView />;
      case 'donor_reward': return <DonorRewardView />;
      case 'medical_reports': return <MedicalReportsView />;
      case 'report_detail': return <ReportDetailView />;
      case 'history': return <HistoryView />;
      case 'settings': return <SettingsView />;
      case 'main': 
      default: return <MainShell />;
    }
  };

  return (
    <div className="flex justify-center bg-gray-200 min-h-screen font-sans selection:bg-teal-200">
      <div className="w-full max-w-md bg-white relative shadow-2xl overflow-x-hidden min-h-screen">
        <AnimatePresence mode="wait">
          {renderView()}
        </AnimatePresence>
      </div>
    </div>
  );
}
