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

# Server Metrics 2026-03-17 23:55:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 105009.1 (29h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1245890
telemt_connections_bad_total 9402
telemt_handshake_timeouts_total 32324
telemt_upstream_connect_attempt_total 23575
telemt_upstream_connect_success_total 23079
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 23575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32685
telemt_me_reconnect_success_total 15550
telemt_me_reader_eof_total 16890
telemt_me_idle_close_by_peer_total 16889
telemt_me_route_drop_no_conn_total 551091
telemt_me_route_drop_channel_closed_total 157
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1144409
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7482
telemt_desync_full_logged_total 2185
telemt_desync_suppressed_total 5297
telemt_desync_frames_bucket_total{bucket="1_2"} 1999
telemt_desync_frames_bucket_total{bucket="3_10"} 2838
telemt_desync_frames_bucket_total{bucket="gt_10"} 2645
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 16313
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15528
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 763
telemt_user_connections_total{user="hello"} 1138631
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 22621715219 (21.07 GB)
telemt_user_octets_to_client{user="hello"} 409925874071 (381.77 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 105260.4 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1319294
telemt_connections_bad_total 61331
telemt_handshake_timeouts_total 45582
telemt_upstream_connect_attempt_total 459231
telemt_upstream_connect_success_total 458314
telemt_upstream_connect_fail_total 917
telemt_upstream_connect_attempts_per_request{bucket="1"} 459231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 917
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 59238
telemt_me_reconnect_success_total 16080
telemt_me_reader_eof_total 18129
telemt_me_idle_close_by_peer_total 18129
telemt_me_route_drop_no_conn_total 343223
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 709070
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3243
telemt_desync_full_logged_total 1067
telemt_desync_suppressed_total 2176
telemt_desync_frames_bucket_total{bucket="1_2"} 631
telemt_desync_frames_bucket_total{bucket="3_10"} 1331
telemt_desync_frames_bucket_total{bucket="gt_10"} 1281
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 17626
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 16064
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1546
telemt_user_connections_total{user="hello"} 1145494
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 15691487818 (14.61 GB)
telemt_user_octets_to_client{user="hello"} 392906537286 (365.92 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 105036.4 (29h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 779805
telemt_connections_bad_total 49804
telemt_handshake_timeouts_total 23771
telemt_upstream_connect_attempt_total 24699
telemt_upstream_connect_success_total 24556
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 24699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13197
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39954
telemt_me_reconnect_success_total 19273
telemt_me_reader_eof_total 21002
telemt_me_idle_close_by_peer_total 20995
telemt_me_route_drop_no_conn_total 317240
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 662932
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2136
telemt_desync_full_logged_total 696
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 607
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 703
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 20182
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19261
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 909
telemt_user_connections_total{user="hello"} 661159
telemt_user_connections_current{user="hello"} 480
telemt_user_octets_from_client{user="hello"} 32008248356 (29.81 GB)
telemt_user_octets_to_client{user="hello"} 292770049900 (272.66 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 105095.9 (29h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1266158
telemt_connections_bad_total 50240
telemt_handshake_timeouts_total 21687
telemt_upstream_connect_attempt_total 84313
telemt_upstream_connect_success_total 83874
telemt_upstream_connect_fail_total 439
telemt_upstream_connect_attempts_per_request{bucket="1"} 84313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 439
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35592
telemt_me_reconnect_success_total 15263
telemt_me_reader_eof_total 16802
telemt_me_idle_close_by_peer_total 16800
telemt_me_route_drop_no_conn_total 520568
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1032811
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3887
telemt_desync_full_logged_total 1283
telemt_desync_suppressed_total 2604
telemt_desync_frames_bucket_total{bucket="1_2"} 950
telemt_desync_frames_bucket_total{bucket="3_10"} 1634
telemt_desync_frames_bucket_total{bucket="gt_10"} 1303
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 16182
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15254
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 919
telemt_user_connections_total{user="hello"} 1095294
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 17230946051 (16.05 GB)
telemt_user_octets_to_client{user="hello"} 504332610097 (469.70 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 105067.8 (29h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 823828
telemt_connections_bad_total 96982
telemt_handshake_timeouts_total 6655
telemt_upstream_connect_attempt_total 43660
telemt_upstream_connect_success_total 43062
telemt_upstream_connect_fail_total 598
telemt_upstream_connect_attempts_per_request{bucket="1"} 43660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 409
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 598
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 56294
telemt_me_reconnect_success_total 21339
telemt_me_reader_eof_total 23205
telemt_me_idle_close_by_peer_total 23203
telemt_me_route_drop_no_conn_total 261459
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 662330
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3146
telemt_desync_full_logged_total 930
telemt_desync_suppressed_total 2216
telemt_desync_frames_bucket_total{bucket="1_2"} 998
telemt_desync_frames_bucket_total{bucket="3_10"} 1255
telemt_desync_frames_bucket_total{bucket="gt_10"} 893
telemt_pool_swap_total 52
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22784
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 21331
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1445
telemt_user_connections_total{user="hello"} 678938
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 13436205152 (12.51 GB)
telemt_user_octets_to_client{user="hello"} 338752810824 (315.49 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 105228.9 (29h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1059467
telemt_connections_bad_total 97123
telemt_handshake_timeouts_total 9563
telemt_upstream_connect_attempt_total 20848
telemt_upstream_connect_success_total 20733
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 20848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10713
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26780
telemt_me_reconnect_success_total 15498
telemt_me_reader_eof_total 16819
telemt_me_idle_close_by_peer_total 16817
telemt_me_route_drop_no_conn_total 708415
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1024316
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 91
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16101
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15484
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 603
telemt_user_connections_total{user="hello"} 885338
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 14285275344 (13.30 GB)
telemt_user_octets_to_client{user="hello"} 374132248088 (348.44 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 52996.0 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381793
telemt_connections_bad_total 44665
telemt_handshake_timeouts_total 10767
telemt_upstream_connect_attempt_total 20039
telemt_upstream_connect_success_total 19856
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 20039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 28658
telemt_me_reconnect_success_total 17060
telemt_me_reader_eof_total 18035
telemt_me_idle_close_by_peer_total 18035
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 95763
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284710
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1050
telemt_desync_full_logged_total 331
telemt_desync_suppressed_total 719
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 445
telemt_desync_frames_bucket_total{bucket="gt_10"} 391
telemt_pool_swap_total 32
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17619
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 17030
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 559
telemt_user_connections_total{user="hello"} 284651
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 22036538433 (20.52 GB)
telemt_user_octets_to_client{user="hello"} 233710396146 (217.66 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 20
```