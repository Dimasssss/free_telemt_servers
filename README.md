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

# Server Metrics 2026-03-17 22:03:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 98281.6 (27h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1198735
telemt_connections_bad_total 8652
telemt_handshake_timeouts_total 31603
telemt_upstream_connect_attempt_total 22305
telemt_upstream_connect_success_total 21812
telemt_upstream_connect_fail_total 493
telemt_upstream_connect_attempts_per_request{bucket="1"} 22305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 493
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31719
telemt_me_reconnect_success_total 14588
telemt_me_reader_eof_total 15860
telemt_me_idle_close_by_peer_total 15859
telemt_me_route_drop_no_conn_total 534618
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1099784
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7282
telemt_desync_full_logged_total 2103
telemt_desync_suppressed_total 5179
telemt_desync_frames_bucket_total{bucket="1_2"} 1942
telemt_desync_frames_bucket_total{bucket="3_10"} 2756
telemt_desync_frames_bucket_total{bucket="gt_10"} 2584
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 15339
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14566
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 751
telemt_user_connections_total{user="hello"} 1094015
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 19954550835 (18.58 GB)
telemt_user_octets_to_client{user="hello"} 391043828919 (364.19 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 98532.8 (27h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1261704
telemt_connections_bad_total 60061
telemt_handshake_timeouts_total 44710
telemt_upstream_connect_attempt_total 457736
telemt_upstream_connect_success_total 456840
telemt_upstream_connect_fail_total 896
telemt_upstream_connect_attempts_per_request{bucket="1"} 457736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30655
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 896
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58066
telemt_me_reconnect_success_total 14911
telemt_me_reader_eof_total 16900
telemt_me_idle_close_by_peer_total 16900
telemt_me_route_drop_no_conn_total 323665
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 655371
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2942
telemt_desync_full_logged_total 947
telemt_desync_suppressed_total 1995
telemt_desync_frames_bucket_total{bucket="1_2"} 557
telemt_desync_frames_bucket_total{bucket="3_10"} 1206
telemt_desync_frames_bucket_total{bucket="gt_10"} 1179
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 16445
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14895
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1534
telemt_user_connections_total{user="hello"} 1091801
telemt_user_connections_current{user="hello"} 976
telemt_user_octets_from_client{user="hello"} 15052384938 (14.02 GB)
telemt_user_octets_to_client{user="hello"} 367594476310 (342.35 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 98308.9 (27h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 721131
telemt_connections_bad_total 44276
telemt_handshake_timeouts_total 22734
telemt_upstream_connect_attempt_total 23362
telemt_upstream_connect_success_total 23224
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 23362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12496
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38925
telemt_me_reconnect_success_total 18247
telemt_me_reader_eof_total 19909
telemt_me_idle_close_by_peer_total 19902
telemt_me_route_drop_no_conn_total 301279
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 619964
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2021
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 1404
telemt_desync_frames_bucket_total{bucket="1_2"} 564
telemt_desync_frames_bucket_total{bucket="3_10"} 793
telemt_desync_frames_bucket_total{bucket="gt_10"} 664
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 19143
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18235
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 896
telemt_user_connections_total{user="hello"} 618234
telemt_user_connections_current{user="hello"} 789
telemt_user_octets_from_client{user="hello"} 30703113860 (28.59 GB)
telemt_user_octets_to_client{user="hello"} 269799004944 (251.27 GB)
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 98368.2 (27h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1218908
telemt_connections_bad_total 40855
telemt_handshake_timeouts_total 21552
telemt_upstream_connect_attempt_total 82996
telemt_upstream_connect_success_total 82564
telemt_upstream_connect_fail_total 431
telemt_upstream_connect_attempts_per_request{bucket="1"} 82995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12222
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 345
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 431
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34583
telemt_me_reconnect_success_total 14260
telemt_me_reader_eof_total 15732
telemt_me_idle_close_by_peer_total 15730
telemt_me_route_drop_no_conn_total 504860
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 996392
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3584
telemt_desync_full_logged_total 1162
telemt_desync_suppressed_total 2422
telemt_desync_frames_bucket_total{bucket="1_2"} 880
telemt_desync_frames_bucket_total{bucket="3_10"} 1503
telemt_desync_frames_bucket_total{bucket="gt_10"} 1201
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 15163
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14251
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 903
telemt_user_connections_total{user="hello"} 1058890
telemt_user_connections_current{user="hello"} 796
telemt_user_octets_from_client{user="hello"} 16643470887 (15.50 GB)
telemt_user_octets_to_client{user="hello"} 460562096773 (428.93 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 98340.3 (27h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 774231
telemt_connections_bad_total 91698
telemt_handshake_timeouts_total 6397
telemt_upstream_connect_attempt_total 41957
telemt_upstream_connect_success_total 41390
telemt_upstream_connect_fail_total 567
telemt_upstream_connect_attempts_per_request{bucket="1"} 41957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 399
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 567
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 54923
telemt_me_reconnect_success_total 19972
telemt_me_reader_eof_total 21781
telemt_me_idle_close_by_peer_total 21779
telemt_me_route_drop_no_conn_total 244496
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 619344
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2817
telemt_desync_full_logged_total 832
telemt_desync_suppressed_total 1985
telemt_desync_frames_bucket_total{bucket="1_2"} 901
telemt_desync_frames_bucket_total{bucket="3_10"} 1129
telemt_desync_frames_bucket_total{bucket="gt_10"} 787
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21402
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 19964
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1430
telemt_user_connections_total{user="hello"} 635955
telemt_user_connections_current{user="hello"} 795
telemt_user_octets_from_client{user="hello"} 12362507136 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 312965500328 (291.47 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 98501.1 (27h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1010249
telemt_connections_bad_total 79092
telemt_handshake_timeouts_total 9467
telemt_upstream_connect_attempt_total 19466
telemt_upstream_connect_success_total 19354
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 19466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9987
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25704
telemt_me_reconnect_success_total 14426
telemt_me_reader_eof_total 15672
telemt_me_idle_close_by_peer_total 15670
telemt_me_route_drop_no_conn_total 689207
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 995645
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2061
telemt_desync_full_logged_total 717
telemt_desync_suppressed_total 1344
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 779
telemt_desync_frames_bucket_total{bucket="gt_10"} 821
telemt_pool_swap_total 84
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15018
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14412
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 592
telemt_user_connections_total{user="hello"} 858674
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 13334336136 (12.42 GB)
telemt_user_octets_to_client{user="hello"} 366084419184 (340.94 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 46268.4 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347670
telemt_connections_bad_total 44351
telemt_handshake_timeouts_total 10537
telemt_upstream_connect_attempt_total 18231
telemt_upstream_connect_success_total 18061
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 18231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27164
telemt_me_reconnect_success_total 15570
telemt_me_reader_eof_total 16457
telemt_me_idle_close_by_peer_total 16457
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 85672
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264108
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 885
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 622
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 326
telemt_pool_swap_total 25
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16113
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15541
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 543
telemt_user_connections_total{user="hello"} 264048
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 21226707405 (19.77 GB)
telemt_user_octets_to_client{user="hello"} 219423524782 (204.35 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 43
```