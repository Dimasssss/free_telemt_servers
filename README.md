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

# Server Metrics 2026-03-18 20:56:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 19856.6 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 473430
telemt_connections_bad_total 27163
telemt_handshake_timeouts_total 9570
telemt_upstream_connect_attempt_total 3486
telemt_upstream_connect_success_total 3482
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 2484
telemt_me_reconnect_success_total 2468
telemt_me_reader_eof_total 2575
telemt_me_idle_close_by_peer_total 2575
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 194147
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 403609
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2401
telemt_desync_full_logged_total 712
telemt_desync_suppressed_total 1689
telemt_desync_frames_bucket_total{bucket="1_2"} 553
telemt_desync_frames_bucket_total{bucket="3_10"} 771
telemt_desync_frames_bucket_total{bucket="gt_10"} 1077
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2514
telemt_me_writer_restored_same_endpoint_total 2450
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 403429
telemt_user_connections_current{user="hello"} 938
telemt_user_octets_from_client{user="hello"} 7785891796 (7.25 GB)
telemt_user_octets_to_client{user="hello"} 148159809536 (137.98 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 24684.5 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2162329
telemt_connections_bad_total 149828
telemt_connections_current 2747
telemt_connections_me_current 2747
telemt_handshake_timeouts_total 36538
telemt_upstream_connect_attempt_total 3858
telemt_upstream_connect_success_total 3833
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1804
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2595
telemt_me_reconnect_success_total 2577
telemt_me_reader_eof_total 2621
telemt_me_idle_close_by_peer_total 2620
telemt_me_route_drop_no_conn_total 1844377
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1873678
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6798
telemt_desync_full_logged_total 2195
telemt_desync_suppressed_total 4603
telemt_desync_frames_bucket_total{bucket="1_2"} 1173
telemt_desync_frames_bucket_total{bucket="3_10"} 2673
telemt_desync_frames_bucket_total{bucket="gt_10"} 2952
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2543
telemt_me_writer_restored_same_endpoint_total 2575
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1869045
telemt_user_connections_current{user="hello"} 2747
telemt_user_octets_from_client{user="hello"} 29079467036 (27.08 GB)
telemt_user_octets_to_client{user="hello"} 651577027648 (606.83 GB)
telemt_user_unique_ips_current{user="hello"} 962
telemt_user_unique_ips_recent_window{user="hello"} 296
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 24612.9 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1653477
telemt_connections_bad_total 134764
telemt_connections_current 2219
telemt_connections_me_current 2219
telemt_handshake_timeouts_total 39877
telemt_upstream_connect_attempt_total 3559
telemt_upstream_connect_success_total 3542
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2302
telemt_me_reconnect_success_total 2282
telemt_me_reader_eof_total 2427
telemt_me_idle_close_by_peer_total 2427
telemt_me_route_drop_no_conn_total 668533
telemt_me_route_drop_channel_closed_total 63
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1332274
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6477
telemt_desync_full_logged_total 1983
telemt_desync_suppressed_total 4494
telemt_desync_frames_bucket_total{bucket="1_2"} 1601
telemt_desync_frames_bucket_total{bucket="3_10"} 2431
telemt_desync_frames_bucket_total{bucket="gt_10"} 2445
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 2339
telemt_me_writer_restored_same_endpoint_total 2265
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 1331474
telemt_user_connections_current{user="hello"} 2219
telemt_user_octets_from_client{user="hello"} 28413581664 (26.46 GB)
telemt_user_octets_to_client{user="hello"} 680227058308 (633.51 GB)
telemt_user_unique_ips_current{user="hello"} 796
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 25327.4 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2289997
telemt_connections_bad_total 74094
telemt_connections_current 1885
telemt_connections_me_current 1885
telemt_handshake_timeouts_total 22715
telemt_upstream_connect_attempt_total 3847
telemt_upstream_connect_success_total 3810
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 3847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1833
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2527
telemt_me_reconnect_success_total 2498
telemt_me_reader_eof_total 2606
telemt_me_idle_close_by_peer_total 2605
telemt_me_route_drop_no_conn_total 3732752
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2031538
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7683
telemt_desync_full_logged_total 2019
telemt_desync_suppressed_total 5664
telemt_desync_frames_bucket_total{bucket="1_2"} 1675
telemt_desync_frames_bucket_total{bucket="3_10"} 3530
telemt_desync_frames_bucket_total{bucket="gt_10"} 2478
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 2517
telemt_me_writer_restored_same_endpoint_total 2487
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2031442
telemt_user_connections_current{user="hello"} 1885
telemt_user_octets_from_client{user="hello"} 21118410160 (19.67 GB)
telemt_user_octets_to_client{user="hello"} 377672297748 (351.73 GB)
telemt_user_unique_ips_current{user="hello"} 691
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 19842.1 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1333358
telemt_connections_bad_total 228596
telemt_handshake_timeouts_total 12740
telemt_upstream_connect_attempt_total 3502
telemt_upstream_connect_success_total 3399
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 3502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1606
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 6930
telemt_me_reconnect_success_total 2398
telemt_me_reader_eof_total 2608
telemt_me_idle_close_by_peer_total 2608
telemt_me_route_drop_no_conn_total 554339
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 986464
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3848
telemt_desync_full_logged_total 1385
telemt_desync_suppressed_total 2463
telemt_desync_frames_bucket_total{bucket="1_2"} 685
telemt_desync_frames_bucket_total{bucket="3_10"} 1303
telemt_desync_frames_bucket_total{bucket="gt_10"} 1860
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2582
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 2372
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 985828
telemt_user_connections_current{user="hello"} 2459
telemt_user_octets_from_client{user="hello"} 17797567008 (16.58 GB)
telemt_user_octets_to_client{user="hello"} 485588659776 (452.24 GB)
telemt_user_unique_ips_current{user="hello"} 910
telemt_user_unique_ips_recent_window{user="hello"} 279
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 24775.3 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375878
telemt_connections_bad_total 10710
telemt_connections_current 592
telemt_connections_me_current 592
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4220
telemt_upstream_connect_attempt_total 8305
telemt_upstream_connect_success_total 8272
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 8305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 332659
telemt_me_reconnect_success_total 3189
telemt_me_reader_eof_total 3273
telemt_me_idle_close_by_peer_total 3273
telemt_me_route_drop_no_conn_total 222042
telemt_me_route_drop_channel_closed_total 105
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334499
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 766
telemt_desync_full_logged_total 281
telemt_desync_suppressed_total 485
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 23
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 3155
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 3178
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 338183
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 7314743341 (6.81 GB)
telemt_user_octets_to_client{user="hello"} 85081065609 (79.24 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 23846.7 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1334849
telemt_connections_bad_total 106342
telemt_connections_current 2206
telemt_connections_me_current 2206
telemt_handshake_timeouts_total 29079
telemt_upstream_connect_attempt_total 3930
telemt_upstream_connect_success_total 3929
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18233
telemt_me_reconnect_success_total 2710
telemt_me_reader_eof_total 2779
telemt_me_idle_close_by_peer_total 2778
telemt_me_route_drop_no_conn_total 596264
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1114663
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5208
telemt_desync_full_logged_total 1706
telemt_desync_suppressed_total 3502
telemt_desync_frames_bucket_total{bucket="1_2"} 1242
telemt_desync_frames_bucket_total{bucket="3_10"} 1765
telemt_desync_frames_bucket_total{bucket="gt_10"} 2201
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2697
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2649
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1113390
telemt_user_connections_current{user="hello"} 2206
telemt_user_octets_from_client{user="hello"} 22419988380 (20.88 GB)
telemt_user_octets_to_client{user="hello"} 646765694588 (602.35 GB)
telemt_user_unique_ips_current{user="hello"} 700
telemt_user_unique_ips_recent_window{user="hello"} 222
```