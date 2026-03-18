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

# Server Metrics 2026-03-18 17:36:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 7860.4 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230544
telemt_connections_bad_total 15234
telemt_handshake_timeouts_total 5914
telemt_upstream_connect_attempt_total 1251
telemt_upstream_connect_success_total 1251
telemt_upstream_connect_attempts_per_request{bucket="1"} 1251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 837
telemt_me_reconnect_success_total 834
telemt_me_reader_eof_total 856
telemt_me_idle_close_by_peer_total 856
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 108418
telemt_me_route_drop_channel_closed_total 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194566
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1082
telemt_desync_full_logged_total 330
telemt_desync_suppressed_total 752
telemt_desync_frames_bucket_total{bucket="1_2"} 254
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 477
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 854
telemt_me_writer_restored_same_endpoint_total 821
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 194479
telemt_user_connections_current{user="hello"} 1330
telemt_user_octets_from_client{user="hello"} 2728660908 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 66032627508 (61.50 GB)
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 12688.5 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1314292
telemt_connections_bad_total 80132
telemt_connections_current 3538
telemt_connections_me_current 3538
telemt_handshake_timeouts_total 25785
telemt_upstream_connect_attempt_total 2221
telemt_upstream_connect_success_total 2209
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 990
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1544
telemt_me_reconnect_success_total 1530
telemt_me_reader_eof_total 1491
telemt_me_idle_close_by_peer_total 1490
telemt_me_route_drop_no_conn_total 1432673
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1143598
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3270
telemt_desync_full_logged_total 1049
telemt_desync_suppressed_total 2221
telemt_desync_frames_bucket_total{bucket="1_2"} 615
telemt_desync_frames_bucket_total{bucket="3_10"} 1284
telemt_desync_frames_bucket_total{bucket="gt_10"} 1371
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1466
telemt_me_writer_restored_same_endpoint_total 1528
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1138914
telemt_user_connections_current{user="hello"} 3538
telemt_user_octets_from_client{user="hello"} 14776879684 (13.76 GB)
telemt_user_octets_to_client{user="hello"} 323247912224 (301.05 GB)
telemt_user_unique_ips_current{user="hello"} 1092
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 12616.7 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 897094
telemt_connections_bad_total 70821
telemt_connections_current 3085
telemt_connections_me_current 3085
telemt_handshake_timeouts_total 20166
telemt_upstream_connect_attempt_total 1745
telemt_upstream_connect_success_total 1736
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1101
telemt_me_reconnect_success_total 1089
telemt_me_reader_eof_total 1150
telemt_me_idle_close_by_peer_total 1150
telemt_me_route_drop_no_conn_total 413453
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 743894
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3023
telemt_desync_full_logged_total 924
telemt_desync_suppressed_total 2099
telemt_desync_frames_bucket_total{bucket="1_2"} 729
telemt_desync_frames_bucket_total{bucket="3_10"} 1128
telemt_desync_frames_bucket_total{bucket="gt_10"} 1166
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1124
telemt_me_writer_restored_same_endpoint_total 1072
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 743531
telemt_user_connections_current{user="hello"} 3085
telemt_user_octets_from_client{user="hello"} 16650500412 (15.51 GB)
telemt_user_octets_to_client{user="hello"} 316593007640 (294.85 GB)
telemt_user_unique_ips_current{user="hello"} 991
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 13331.1 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1324466
telemt_connections_bad_total 27976
telemt_connections_current 2985
telemt_connections_me_current 2985
telemt_handshake_timeouts_total 15680
telemt_upstream_connect_attempt_total 2050
telemt_upstream_connect_success_total 2036
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1354
telemt_me_reconnect_success_total 1336
telemt_me_reader_eof_total 1365
telemt_me_idle_close_by_peer_total 1364
telemt_me_route_drop_no_conn_total 2234723
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1187135
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4387
telemt_desync_full_logged_total 1112
telemt_desync_suppressed_total 3275
telemt_desync_frames_bucket_total{bucket="1_2"} 1020
telemt_desync_frames_bucket_total{bucket="3_10"} 2009
telemt_desync_frames_bucket_total{bucket="gt_10"} 1358
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1334
telemt_me_writer_restored_same_endpoint_total 1325
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 1187061
telemt_user_connections_current{user="hello"} 2985
telemt_user_octets_from_client{user="hello"} 10772336608 (10.03 GB)
telemt_user_octets_to_client{user="hello"} 200186742704 (186.44 GB)
telemt_user_unique_ips_current{user="hello"} 889
telemt_user_unique_ips_recent_window{user="hello"} 411
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 7846.1 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 588094
telemt_connections_bad_total 104242
telemt_handshake_timeouts_total 5560
telemt_upstream_connect_attempt_total 1419
telemt_upstream_connect_success_total 1376
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 1419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 643
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 1956
telemt_me_reconnect_success_total 954
telemt_me_reader_eof_total 987
telemt_me_idle_close_by_peer_total 987
telemt_me_route_drop_no_conn_total 239448
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 434444
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1696
telemt_desync_full_logged_total 565
telemt_desync_suppressed_total 1131
telemt_desync_frames_bucket_total{bucket="1_2"} 311
telemt_desync_frames_bucket_total{bucket="3_10"} 567
telemt_desync_frames_bucket_total{bucket="gt_10"} 818
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 997
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 928
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 433967
telemt_user_connections_current{user="hello"} 3270
telemt_user_octets_from_client{user="hello"} 6865361428 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 183170946832 (170.59 GB)
telemt_user_unique_ips_current{user="hello"} 1082
telemt_user_unique_ips_recent_window{user="hello"} 458
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 12781.4 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236598
telemt_connections_bad_total 8196
telemt_connections_current 881
telemt_connections_me_current 881
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2543
telemt_upstream_connect_attempt_total 6350
telemt_upstream_connect_success_total 6337
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 6350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2892
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 331286
telemt_me_reconnect_success_total 1821
telemt_me_reader_eof_total 1801
telemt_me_idle_close_by_peer_total 1801
telemt_me_route_drop_no_conn_total 156488
telemt_me_route_drop_channel_closed_total 61
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210328
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 419
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 269
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 169
telemt_pool_swap_total 10
telemt_pool_stale_pick_total 46
telemt_me_writer_removed_unexpected_total 1761
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1810
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 214047
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 3054720353 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 43437209113 (40.45 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 11850.6 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 720494
telemt_connections_bad_total 49914
telemt_connections_current 2948
telemt_connections_me_current 2948
telemt_handshake_timeouts_total 13543
telemt_upstream_connect_attempt_total 2111
telemt_upstream_connect_success_total 2110
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 16975
telemt_me_reconnect_success_total 1461
telemt_me_reader_eof_total 1444
telemt_me_idle_close_by_peer_total 1444
telemt_me_route_drop_no_conn_total 401079
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 604922
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2324
telemt_desync_full_logged_total 792
telemt_desync_suppressed_total 1532
telemt_desync_frames_bucket_total{bucket="1_2"} 590
telemt_desync_frames_bucket_total{bucket="3_10"} 823
telemt_desync_frames_bucket_total{bucket="gt_10"} 911
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1424
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1400
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 603948
telemt_user_connections_current{user="hello"} 2948
telemt_user_octets_from_client{user="hello"} 11446624180 (10.66 GB)
telemt_user_octets_to_client{user="hello"} 297200477104 (276.79 GB)
telemt_user_unique_ips_current{user="hello"} 925
telemt_user_unique_ips_recent_window{user="hello"} 393
```