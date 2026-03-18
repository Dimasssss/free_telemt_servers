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

# Server Metrics 2026-03-18 16:14:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2934.2 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101335
telemt_connections_bad_total 9724
telemt_handshake_timeouts_total 3695
telemt_upstream_connect_attempt_total 423
telemt_upstream_connect_success_total 423
telemt_upstream_connect_attempts_per_request{bucket="1"} 423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 224
telemt_me_reconnect_success_total 223
telemt_me_reader_eof_total 216
telemt_me_idle_close_by_peer_total 216
telemt_me_route_drop_no_conn_total 66422
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82078
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 459
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 340
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 142
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 229
telemt_me_writer_restored_same_endpoint_total 212
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 82049
telemt_user_connections_current{user="hello"} 1570
telemt_user_octets_from_client{user="hello"} 1129314564 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 25445985152 (23.70 GB)
telemt_user_unique_ips_current{user="hello"} 520
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 7764.1 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 840273
telemt_connections_bad_total 55539
telemt_connections_current 3425
telemt_connections_me_current 3425
telemt_handshake_timeouts_total 14119
telemt_upstream_connect_attempt_total 1445
telemt_upstream_connect_success_total 1437
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1018
telemt_me_reconnect_success_total 1008
telemt_me_reader_eof_total 931
telemt_me_idle_close_by_peer_total 930
telemt_me_route_drop_no_conn_total 905917
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 730360
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1967
telemt_desync_full_logged_total 608
telemt_desync_suppressed_total 1359
telemt_desync_frames_bucket_total{bucket="1_2"} 398
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 767
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 938
telemt_me_writer_restored_same_endpoint_total 1006
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 729550
telemt_user_connections_current{user="hello"} 3425
telemt_user_octets_from_client{user="hello"} 6712762740 (6.25 GB)
telemt_user_octets_to_client{user="hello"} 195120371656 (181.72 GB)
telemt_user_unique_ips_current{user="hello"} 1110
telemt_user_unique_ips_recent_window{user="hello"} 484
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 7692.1 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 550678
telemt_connections_bad_total 37220
telemt_connections_current 2955
telemt_connections_me_current 2955
telemt_handshake_timeouts_total 11291
telemt_upstream_connect_attempt_total 1103
telemt_upstream_connect_success_total 1098
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 678
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 692
telemt_me_idle_close_by_peer_total 692
telemt_me_route_drop_no_conn_total 296707
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 465751
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1742
telemt_desync_full_logged_total 495
telemt_desync_suppressed_total 1247
telemt_desync_frames_bucket_total{bucket="1_2"} 398
telemt_desync_frames_bucket_total{bucket="3_10"} 658
telemt_desync_frames_bucket_total{bucket="gt_10"} 686
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 688
telemt_me_writer_restored_same_endpoint_total 651
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 465473
telemt_user_connections_current{user="hello"} 2955
telemt_user_octets_from_client{user="hello"} 8803185440 (8.20 GB)
telemt_user_octets_to_client{user="hello"} 179015005184 (166.72 GB)
telemt_user_unique_ips_current{user="hello"} 965
telemt_user_unique_ips_recent_window{user="hello"} 422
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 8406.2 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 732222
telemt_connections_bad_total 9431
telemt_connections_current 2645
telemt_connections_me_current 2645
telemt_handshake_timeouts_total 10374
telemt_upstream_connect_attempt_total 1419
telemt_upstream_connect_success_total 1408
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 940
telemt_me_reconnect_success_total 931
telemt_me_reader_eof_total 930
telemt_me_idle_close_by_peer_total 929
telemt_me_route_drop_no_conn_total 1171544
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 665277
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2598
telemt_desync_full_logged_total 661
telemt_desync_suppressed_total 1937
telemt_desync_frames_bucket_total{bucket="1_2"} 562
telemt_desync_frames_bucket_total{bucket="3_10"} 1186
telemt_desync_frames_bucket_total{bucket="gt_10"} 850
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 918
telemt_me_writer_restored_same_endpoint_total 920
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 665258
telemt_user_connections_current{user="hello"} 2645
telemt_user_octets_from_client{user="hello"} 4968514948 (4.63 GB)
telemt_user_octets_to_client{user="hello"} 130047574264 (121.12 GB)
telemt_user_unique_ips_current{user="hello"} 834
telemt_user_unique_ips_recent_window{user="hello"} 348
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2920.8 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235321
telemt_connections_bad_total 44002
telemt_handshake_timeouts_total 2918
telemt_upstream_connect_attempt_total 544
telemt_upstream_connect_success_total 526
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 329
telemt_me_reconnect_success_total 324
telemt_me_reader_eof_total 296
telemt_me_idle_close_by_peer_total 296
telemt_me_route_drop_no_conn_total 112319
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170546
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 577
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 319
telemt_me_writer_restored_same_endpoint_total 298
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_user_connections_total{user="hello"} 170284
telemt_user_connections_current{user="hello"} 3074
telemt_user_octets_from_client{user="hello"} 2672204400 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 63284439284 (58.94 GB)
telemt_user_unique_ips_current{user="hello"} 1022
telemt_user_unique_ips_recent_window{user="hello"} 493
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 7856.7 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152447
telemt_connections_bad_total 5899
telemt_connections_current 923
telemt_connections_me_current 923
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1335
telemt_upstream_connect_attempt_total 5549
telemt_upstream_connect_success_total 5539
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 5549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2400
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 330748
telemt_me_reconnect_success_total 1289
telemt_me_reader_eof_total 1222
telemt_me_idle_close_by_peer_total 1222
telemt_me_route_drop_no_conn_total 85334
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134397
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 289
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 181
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1218
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1278
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 138140
telemt_user_connections_current{user="hello"} 923
telemt_user_octets_from_client{user="hello"} 2076928781 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 30016006481 (27.95 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 6925.4 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433502
telemt_connections_bad_total 15489
telemt_connections_current 2650
telemt_connections_me_current 2650
telemt_handshake_timeouts_total 6140
telemt_upstream_connect_attempt_total 1337
telemt_upstream_connect_success_total 1337
telemt_upstream_connect_attempts_per_request{bucket="1"} 1337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 16461
telemt_me_reconnect_success_total 952
telemt_me_reader_eof_total 896
telemt_me_idle_close_by_peer_total 896
telemt_me_route_drop_no_conn_total 292920
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374561
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1004
telemt_desync_full_logged_total 384
telemt_desync_suppressed_total 620
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 461
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 907
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 891
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 374835
telemt_user_connections_current{user="hello"} 2650
telemt_user_octets_from_client{user="hello"} 5313388316 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 159113921056 (148.19 GB)
telemt_user_unique_ips_current{user="hello"} 820
telemt_user_unique_ips_recent_window{user="hello"} 365
```