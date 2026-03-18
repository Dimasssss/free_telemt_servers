# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 19:34:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14949.2 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385952
telemt_connections_bad_total 23087
telemt_handshake_timeouts_total 8299
telemt_upstream_connect_attempt_total 2685
telemt_upstream_connect_success_total 2685
telemt_upstream_connect_attempts_per_request{bucket="1"} 2685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1335
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 1925
telemt_me_reconnect_success_total 1917
telemt_me_reader_eof_total 1990
telemt_me_idle_close_by_peer_total 1990
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 164653
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 333350
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2001
telemt_desync_full_logged_total 561
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 475
telemt_desync_frames_bucket_total{bucket="3_10"} 625
telemt_desync_frames_bucket_total{bucket="gt_10"} 901
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1949
telemt_me_writer_restored_same_endpoint_total 1899
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 333229
telemt_user_connections_current{user="hello"} 1291
telemt_user_octets_from_client{user="hello"} 6788275180 (6.32 GB)
telemt_user_octets_to_client{user="hello"} 116092592908 (108.12 GB)
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 19777.3 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1889334
telemt_connections_bad_total 128823
telemt_connections_current 3655
telemt_connections_me_current 3655
telemt_handshake_timeouts_total 32547
telemt_upstream_connect_attempt_total 3133
telemt_upstream_connect_success_total 3117
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 2139
telemt_me_reconnect_success_total 2122
telemt_me_reader_eof_total 2131
telemt_me_idle_close_by_peer_total 2130
telemt_me_route_drop_no_conn_total 1737563
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1634747
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5611
telemt_desync_full_logged_total 1788
telemt_desync_suppressed_total 3823
telemt_desync_frames_bucket_total{bucket="1_2"} 982
telemt_desync_frames_bucket_total{bucket="3_10"} 2244
telemt_desync_frames_bucket_total{bucket="gt_10"} 2385
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2075
telemt_me_writer_restored_same_endpoint_total 2120
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1629929
telemt_user_connections_current{user="hello"} 3655
telemt_user_octets_from_client{user="hello"} 25152765148 (23.43 GB)
telemt_user_octets_to_client{user="hello"} 527327787984 (491.11 GB)
telemt_user_unique_ips_current{user="hello"} 1190
telemt_user_unique_ips_recent_window{user="hello"} 426
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 19706.2 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1434755
telemt_connections_bad_total 121682
telemt_connections_current 3224
telemt_connections_me_current 3224
telemt_handshake_timeouts_total 30478
telemt_upstream_connect_attempt_total 2811
telemt_upstream_connect_success_total 2795
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1814
telemt_me_reconnect_success_total 1797
telemt_me_reader_eof_total 1906
telemt_me_idle_close_by_peer_total 1906
telemt_me_route_drop_no_conn_total 585356
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1145774
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5371
telemt_desync_full_logged_total 1665
telemt_desync_suppressed_total 3706
telemt_desync_frames_bucket_total{bucket="1_2"} 1333
telemt_desync_frames_bucket_total{bucket="3_10"} 2042
telemt_desync_frames_bucket_total{bucket="gt_10"} 1996
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 1843
telemt_me_writer_restored_same_endpoint_total 1780
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1145074
telemt_user_connections_current{user="hello"} 3224
telemt_user_octets_from_client{user="hello"} 24865650736 (23.16 GB)
telemt_user_octets_to_client{user="hello"} 550177010184 (512.39 GB)
telemt_user_unique_ips_current{user="hello"} 1035
telemt_user_unique_ips_recent_window{user="hello"} 351
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 20420.4 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2086722
telemt_connections_bad_total 52440
telemt_connections_current 2429
telemt_connections_me_current 2429
telemt_handshake_timeouts_total 21283
telemt_upstream_connect_attempt_total 3100
telemt_upstream_connect_success_total 3070
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 3100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2047
telemt_me_reconnect_success_total 2022
telemt_me_reader_eof_total 2096
telemt_me_idle_close_by_peer_total 2095
telemt_me_route_drop_no_conn_total 3646078
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1866720
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6896
telemt_desync_full_logged_total 1744
telemt_desync_suppressed_total 5152
telemt_desync_frames_bucket_total{bucket="1_2"} 1531
telemt_desync_frames_bucket_total{bucket="3_10"} 3233
telemt_desync_frames_bucket_total{bucket="gt_10"} 2132
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2034
telemt_me_writer_restored_same_endpoint_total 2011
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 1866631
telemt_user_connections_current{user="hello"} 2429
telemt_user_octets_from_client{user="hello"} 17024409180 (15.86 GB)
telemt_user_octets_to_client{user="hello"} 301402550348 (280.70 GB)
telemt_user_unique_ips_current{user="hello"} 818
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 14935.2 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1094375
telemt_connections_bad_total 194193
telemt_handshake_timeouts_total 10533
telemt_upstream_connect_attempt_total 2672
telemt_upstream_connect_success_total 2590
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 2672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 3913
telemt_me_reconnect_success_total 1817
telemt_me_reader_eof_total 1934
telemt_me_idle_close_by_peer_total 1934
telemt_me_route_drop_no_conn_total 476689
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 804901
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2844
telemt_desync_full_logged_total 1009
telemt_desync_suppressed_total 1835
telemt_desync_frames_bucket_total{bucket="1_2"} 528
telemt_desync_frames_bucket_total{bucket="3_10"} 975
telemt_desync_frames_bucket_total{bucket="gt_10"} 1341
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1912
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1791
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 804294
telemt_user_connections_current{user="hello"} 3161
telemt_user_octets_from_client{user="hello"} 13897025840 (12.94 GB)
telemt_user_octets_to_client{user="hello"} 371647028028 (346.12 GB)
telemt_user_unique_ips_current{user="hello"} 1064
telemt_user_unique_ips_recent_window{user="hello"} 395
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 19868.6 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330204
telemt_connections_bad_total 10510
telemt_connections_current 726
telemt_connections_me_current 726
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3547
telemt_upstream_connect_attempt_total 7469
telemt_upstream_connect_success_total 7440
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3551
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 332070
telemt_me_reconnect_success_total 2600
telemt_me_reader_eof_total 2636
telemt_me_idle_close_by_peer_total 2636
telemt_me_route_drop_no_conn_total 203772
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294015
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 585
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 369
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2555
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2589
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 297699
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 4792161809 (4.46 GB)
telemt_user_octets_to_client{user="hello"} 64726503821 (60.28 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 18939.6 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1137360
telemt_connections_bad_total 96072
telemt_connections_current 2950
telemt_connections_me_current 2950
telemt_handshake_timeouts_total 21781
telemt_upstream_connect_attempt_total 3149
telemt_upstream_connect_success_total 3148
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17700
telemt_me_reconnect_success_total 2180
telemt_me_reader_eof_total 2211
telemt_me_idle_close_by_peer_total 2211
telemt_me_route_drop_no_conn_total 525846
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 942612
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3942
telemt_desync_full_logged_total 1338
telemt_desync_suppressed_total 2604
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1384
telemt_desync_frames_bucket_total{bucket="gt_10"} 1666
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2158
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2119
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 941400
telemt_user_connections_current{user="hello"} 2950
telemt_user_octets_from_client{user="hello"} 18619559136 (17.34 GB)
telemt_user_octets_to_client{user="hello"} 537676838496 (500.75 GB)
telemt_user_unique_ips_current{user="hello"} 889
telemt_user_unique_ips_recent_window{user="hello"} 317
```