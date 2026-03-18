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

# Server Metrics 2026-03-18 23:14:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 5159.9 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61709
telemt_connections_bad_total 6286
telemt_connections_current 671
telemt_connections_me_current 671
telemt_handshake_timeouts_total 717
telemt_upstream_connect_attempt_total 942
telemt_upstream_connect_success_total 930
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 653
telemt_me_reconnect_success_total 651
telemt_me_reader_eof_total 656
telemt_me_idle_close_by_peer_total 656
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 21962
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54359
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 273
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 179
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 646
telemt_me_writer_restored_same_endpoint_total 640
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 51602
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 550142208 (524.66 MB)
telemt_user_octets_to_client{user="hello"} 22603427936 (21.05 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 5163.2 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149184
telemt_connections_bad_total 12634
telemt_connections_current 1686
telemt_connections_me_current 1686
telemt_handshake_timeouts_total 1145
telemt_upstream_connect_attempt_total 938
telemt_upstream_connect_success_total 917
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 633
telemt_me_reconnect_success_total 632
telemt_me_reader_eof_total 640
telemt_me_idle_close_by_peer_total 640
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 47371
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127446
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 480
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 646
telemt_me_writer_restored_same_endpoint_total 621
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 127526
telemt_user_connections_current{user="hello"} 1686
telemt_user_octets_from_client{user="hello"} 9792991160 (9.12 GB)
telemt_user_octets_to_client{user="hello"} 50781636924 (47.29 GB)
telemt_user_unique_ips_current{user="hello"} 652
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 5160.3 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116562
telemt_connections_bad_total 17003
telemt_connections_current 1178
telemt_connections_me_current 1178
telemt_handshake_timeouts_total 3200
telemt_upstream_connect_attempt_total 986
telemt_upstream_connect_success_total 986
telemt_upstream_connect_attempts_per_request{bucket="1"} 986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 468
telemt_me_reconnect_attempts_total 703
telemt_me_reconnect_success_total 702
telemt_me_reader_eof_total 715
telemt_me_idle_close_by_peer_total 715
telemt_me_route_drop_no_conn_total 40132
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93101
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 401
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 167
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 710
telemt_me_writer_restored_same_endpoint_total 686
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 93103
telemt_user_connections_current{user="hello"} 1178
telemt_user_octets_from_client{user="hello"} 1326270480 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 59941816404 (55.83 GB)
telemt_user_unique_ips_current{user="hello"} 517
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 5213.7 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130701
telemt_connections_bad_total 23307
telemt_connections_current 1094
telemt_connections_me_current 1094
telemt_handshake_timeouts_total 2919
telemt_upstream_connect_attempt_total 900
telemt_upstream_connect_success_total 900
telemt_upstream_connect_attempts_per_request{bucket="1"} 900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 620
telemt_me_reconnect_success_total 618
telemt_me_reader_eof_total 628
telemt_me_idle_close_by_peer_total 628
telemt_me_route_drop_no_conn_total 53491
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98540
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 225
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 628
telemt_me_writer_restored_same_endpoint_total 594
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 98469
telemt_user_connections_current{user="hello"} 1094
telemt_user_octets_from_client{user="hello"} 1004372960 (957.84 MB)
telemt_user_octets_to_client{user="hello"} 36003195416 (33.53 GB)
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 5157.0 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126186
telemt_connections_bad_total 5613
telemt_connections_current 1353
telemt_connections_me_current 1353
telemt_handshake_timeouts_total 3925
telemt_upstream_connect_attempt_total 925
telemt_upstream_connect_success_total 919
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 635
telemt_me_reconnect_success_total 633
telemt_me_reader_eof_total 640
telemt_me_idle_close_by_peer_total 640
telemt_me_route_drop_no_conn_total 37899
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100071
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 266
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 635
telemt_me_writer_restored_same_endpoint_total 609
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 100029
telemt_user_connections_current{user="hello"} 1353
telemt_user_octets_from_client{user="hello"} 1314635604 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 60095904164 (55.97 GB)
telemt_user_unique_ips_current{user="hello"} 570
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 5168.5 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29498
telemt_connections_bad_total 6180
telemt_connections_current 382
telemt_connections_me_current 382
telemt_handshake_timeouts_total 85
telemt_upstream_connect_attempt_total 1569
telemt_upstream_connect_success_total 1520
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 1569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 663
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 2043
telemt_me_reconnect_success_total 1241
telemt_me_reader_eof_total 1237
telemt_me_idle_close_by_peer_total 1237
telemt_me_route_drop_no_conn_total 9721
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22559
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1240
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 1211
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 22559
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 290317076 (276.87 MB)
telemt_user_octets_to_client{user="hello"} 16417503052 (15.29 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 5159.3 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95056
telemt_connections_bad_total 12801
telemt_connections_current 1147
telemt_connections_me_current 1147
telemt_handshake_timeouts_total 2940
telemt_upstream_connect_attempt_total 933
telemt_upstream_connect_success_total 933
telemt_upstream_connect_attempts_per_request{bucket="1"} 933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 649
telemt_me_reconnect_success_total 647
telemt_me_reader_eof_total 659
telemt_me_idle_close_by_peer_total 659
telemt_me_route_drop_no_conn_total 28093
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77236
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 576
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 358
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 656
telemt_me_writer_restored_same_endpoint_total 632
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 77254
telemt_user_connections_current{user="hello"} 1147
telemt_user_octets_from_client{user="hello"} 819428752 (781.47 MB)
telemt_user_octets_to_client{user="hello"} 45135912800 (42.04 GB)
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 108
```