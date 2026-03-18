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

# Server Metrics 2026-03-18 16:29:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3856.7 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125436
telemt_connections_bad_total 10459
telemt_handshake_timeouts_total 4435
telemt_upstream_connect_attempt_total 545
telemt_upstream_connect_success_total 545
telemt_upstream_connect_attempts_per_request{bucket="1"} 545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 303
telemt_me_reconnect_success_total 302
telemt_me_reader_eof_total 302
telemt_me_idle_close_by_peer_total 302
telemt_me_route_drop_no_conn_total 74270
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102342
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 620
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 445
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 313
telemt_me_writer_restored_same_endpoint_total 291
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 102305
telemt_user_connections_current{user="hello"} 1437
telemt_user_octets_from_client{user="hello"} 1371474664 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 34949056048 (32.55 GB)
telemt_user_unique_ips_current{user="hello"} 483
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 8684.9 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 910952
telemt_connections_bad_total 59494
telemt_connections_current 3701
telemt_connections_me_current 3701
telemt_handshake_timeouts_total 14598
telemt_upstream_connect_attempt_total 1630
telemt_upstream_connect_success_total 1621
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1159
telemt_me_reconnect_success_total 1149
telemt_me_reader_eof_total 1088
telemt_me_idle_close_by_peer_total 1087
telemt_me_route_drop_no_conn_total 933356
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 792142
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2208
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1520
telemt_desync_frames_bucket_total{bucket="1_2"} 435
telemt_desync_frames_bucket_total{bucket="3_10"} 892
telemt_desync_frames_bucket_total{bucket="gt_10"} 881
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1079
telemt_me_writer_restored_same_endpoint_total 1147
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 791318
telemt_user_connections_current{user="hello"} 3701
telemt_user_octets_from_client{user="hello"} 8752566048 (8.15 GB)
telemt_user_octets_to_client{user="hello"} 221718513984 (206.49 GB)
telemt_user_unique_ips_current{user="hello"} 1152
telemt_user_unique_ips_recent_window{user="hello"} 510
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 8614.0 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 606690
telemt_connections_bad_total 41825
telemt_connections_current 3144
telemt_connections_me_current 3144
telemt_handshake_timeouts_total 12961
telemt_upstream_connect_attempt_total 1244
telemt_upstream_connect_success_total 1239
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 776
telemt_me_reconnect_success_total 766
telemt_me_reader_eof_total 801
telemt_me_idle_close_by_peer_total 801
telemt_me_route_drop_no_conn_total 316792
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 513228
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1978
telemt_desync_full_logged_total 581
telemt_desync_suppressed_total 1397
telemt_desync_frames_bucket_total{bucket="1_2"} 438
telemt_desync_frames_bucket_total{bucket="3_10"} 764
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 789
telemt_me_writer_restored_same_endpoint_total 749
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 512944
telemt_user_connections_current{user="hello"} 3144
telemt_user_octets_from_client{user="hello"} 9564476152 (8.91 GB)
telemt_user_octets_to_client{user="hello"} 202192844032 (188.31 GB)
telemt_user_unique_ips_current{user="hello"} 980
telemt_user_unique_ips_recent_window{user="hello"} 373
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 9327.7 (2h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 823144
telemt_connections_bad_total 13610
telemt_connections_current 2551
telemt_connections_me_current 2551
telemt_handshake_timeouts_total 11191
telemt_upstream_connect_attempt_total 1536
telemt_upstream_connect_success_total 1524
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 1013
telemt_me_reconnect_success_total 1004
telemt_me_reader_eof_total 1009
telemt_me_idle_close_by_peer_total 1008
telemt_me_route_drop_no_conn_total 1293828
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 744237
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2897
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 2150
telemt_desync_frames_bucket_total{bucket="1_2"} 641
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 937
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 994
telemt_me_writer_restored_same_endpoint_total 993
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 744214
telemt_user_connections_current{user="hello"} 2551
telemt_user_octets_from_client{user="hello"} 6176689092 (5.75 GB)
telemt_user_octets_to_client{user="hello"} 143860493420 (133.98 GB)
telemt_user_unique_ips_current{user="hello"} 839
telemt_user_unique_ips_recent_window{user="hello"} 452
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3842.4 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307852
telemt_connections_bad_total 62319
telemt_handshake_timeouts_total 3300
telemt_upstream_connect_attempt_total 745
telemt_upstream_connect_success_total 718
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 301
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 1470
telemt_me_reconnect_success_total 472
telemt_me_reader_eof_total 481
telemt_me_idle_close_by_peer_total 481
telemt_me_route_drop_no_conn_total 130609
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218099
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 748
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 490
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 390
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 504
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 446
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 217807
telemt_user_connections_current{user="hello"} 2909
telemt_user_octets_from_client{user="hello"} 3296333872 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 81958003436 (76.33 GB)
telemt_user_unique_ips_current{user="hello"} 1012
telemt_user_unique_ips_recent_window{user="hello"} 401
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 8777.5 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167609
telemt_connections_bad_total 6812
telemt_connections_current 914
telemt_connections_me_current 914
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1528
telemt_upstream_connect_attempt_total 5727
telemt_upstream_connect_success_total 5716
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 5727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2516
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 330881
telemt_me_reconnect_success_total 1420
telemt_me_reader_eof_total 1369
telemt_me_idle_close_by_peer_total 1369
telemt_me_route_drop_no_conn_total 92763
telemt_me_route_drop_channel_closed_total 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147722
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 326
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 210
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1352
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1409
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 151455
telemt_user_connections_current{user="hello"} 914
telemt_user_octets_from_client{user="hello"} 2305739521 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 32648639869 (30.41 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 7846.8 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481225
telemt_connections_bad_total 18102
telemt_connections_current 2381
telemt_connections_me_current 2381
telemt_handshake_timeouts_total 8243
telemt_upstream_connect_attempt_total 1492
telemt_upstream_connect_success_total 1492
telemt_upstream_connect_attempts_per_request{bucket="1"} 1492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 16573
telemt_me_reconnect_success_total 1063
telemt_me_reader_eof_total 1018
telemt_me_idle_close_by_peer_total 1018
telemt_me_route_drop_no_conn_total 309366
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 414751
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1207
telemt_desync_full_logged_total 449
telemt_desync_suppressed_total 758
telemt_desync_frames_bucket_total{bucket="1_2"} 246
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 541
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1019
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1002
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 415018
telemt_user_connections_current{user="hello"} 2381
telemt_user_octets_from_client{user="hello"} 6942066380 (6.47 GB)
telemt_user_octets_to_client{user="hello"} 179089933204 (166.79 GB)
telemt_user_unique_ips_current{user="hello"} 786
telemt_user_unique_ips_recent_window{user="hello"} 334
```