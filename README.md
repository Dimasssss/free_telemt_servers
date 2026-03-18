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

# Server Metrics 2026-03-18 03:34:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 118145.3 (32h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1350179
telemt_connections_bad_total 10398
telemt_handshake_timeouts_total 33458
telemt_upstream_connect_attempt_total 26124
telemt_upstream_connect_success_total 25614
telemt_upstream_connect_fail_total 510
telemt_upstream_connect_attempts_per_request{bucket="1"} 26124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 510
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34571
telemt_me_reconnect_success_total 17428
telemt_me_reader_eof_total 18915
telemt_me_idle_close_by_peer_total 18914
telemt_me_route_drop_no_conn_total 580610
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1243379
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7880
telemt_desync_full_logged_total 2345
telemt_desync_suppressed_total 5535
telemt_desync_frames_bucket_total{bucket="1_2"} 2083
telemt_desync_frames_bucket_total{bucket="3_10"} 3015
telemt_desync_frames_bucket_total{bucket="gt_10"} 2782
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 18224
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17406
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 796
telemt_user_connections_total{user="hello"} 1237583
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 25073392491 (23.35 GB)
telemt_user_octets_to_client{user="hello"} 439735471383 (409.54 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 118396.8 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1431720
telemt_connections_bad_total 64623
telemt_handshake_timeouts_total 47786
telemt_upstream_connect_attempt_total 469287
telemt_upstream_connect_success_total 467689
telemt_upstream_connect_fail_total 1598
telemt_upstream_connect_attempts_per_request{bucket="1"} 469287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33947
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1598
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 125593
telemt_me_reconnect_success_total 18870
telemt_me_reader_eof_total 21108
telemt_me_idle_close_by_peer_total 21095
telemt_me_route_drop_no_conn_total 369701
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 805098
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3718
telemt_desync_full_logged_total 1279
telemt_desync_suppressed_total 2439
telemt_desync_frames_bucket_total{bucket="1_2"} 728
telemt_desync_frames_bucket_total{bucket="3_10"} 1540
telemt_desync_frames_bucket_total{bucket="gt_10"} 1450
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 20484
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 18852
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1614
telemt_user_connections_total{user="hello"} 1247430
telemt_user_connections_current{user="hello"} 855
telemt_user_octets_from_client{user="hello"} 16726053177 (15.58 GB)
telemt_user_octets_to_client{user="hello"} 444468891662 (413.94 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 118172.8 (32h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 875902
telemt_connections_bad_total 61630
telemt_handshake_timeouts_total 25139
telemt_upstream_connect_attempt_total 27464
telemt_upstream_connect_success_total 27305
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 27464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42061
telemt_me_reconnect_success_total 21365
telemt_me_reader_eof_total 23238
telemt_me_idle_close_by_peer_total 23231
telemt_me_route_drop_no_conn_total 341687
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 736901
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2313
telemt_desync_full_logged_total 752
telemt_desync_suppressed_total 1561
telemt_desync_frames_bucket_total{bucket="1_2"} 665
telemt_desync_frames_bucket_total{bucket="3_10"} 890
telemt_desync_frames_bucket_total{bucket="gt_10"} 758
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 22297
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21353
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 932
telemt_user_connections_total{user="hello"} 735016
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 44395095332 (41.35 GB)
telemt_user_octets_to_client{user="hello"} 330267784348 (307.59 GB)
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 118232.3 (32h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1352212
telemt_connections_bad_total 63559
telemt_handshake_timeouts_total 23742
telemt_upstream_connect_attempt_total 90356
telemt_upstream_connect_success_total 87925
telemt_upstream_connect_fail_total 2431
telemt_upstream_connect_attempts_per_request{bucket="1"} 90356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 373
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2431
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37670
telemt_me_reconnect_success_total 17263
telemt_me_reader_eof_total 18973
telemt_me_idle_close_by_peer_total 18970
telemt_me_route_drop_no_conn_total 552247
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1097799
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4089
telemt_desync_full_logged_total 1347
telemt_desync_suppressed_total 2742
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1705
telemt_desync_frames_bucket_total{bucket="gt_10"} 1380
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 18222
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17243
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 959
telemt_user_connections_total{user="hello"} 1161163
telemt_user_connections_current{user="hello"} 727
telemt_user_octets_from_client{user="hello"} 18080830638 (16.84 GB)
telemt_user_octets_to_client{user="hello"} 554986276842 (516.87 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 118204.2 (32h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 911238
telemt_connections_bad_total 101591
telemt_handshake_timeouts_total 7269
telemt_upstream_connect_attempt_total 47186
telemt_upstream_connect_success_total 46542
telemt_upstream_connect_fail_total 644
telemt_upstream_connect_attempts_per_request{bucket="1"} 47186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 644
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59127
telemt_me_reconnect_success_total 24163
telemt_me_reader_eof_total 26180
telemt_me_idle_close_by_peer_total 26177
telemt_me_route_drop_no_conn_total 291062
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738211
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3332
telemt_desync_full_logged_total 1008
telemt_desync_suppressed_total 2324
telemt_desync_frames_bucket_total{bucket="1_2"} 1030
telemt_desync_frames_bucket_total{bucket="3_10"} 1328
telemt_desync_frames_bucket_total{bucket="gt_10"} 974
telemt_pool_swap_total 62
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25633
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24155
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1470
telemt_user_connections_total{user="hello"} 754728
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 14388667724 (13.40 GB)
telemt_user_octets_to_client{user="hello"} 372575251920 (346.99 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 118365.0 (32h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1151325
telemt_connections_bad_total 126841
telemt_handshake_timeouts_total 10169
telemt_upstream_connect_attempt_total 23583
telemt_upstream_connect_success_total 23447
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 23583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12065
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28848
telemt_me_reconnect_success_total 17556
telemt_me_reader_eof_total 19032
telemt_me_idle_close_by_peer_total 19030
telemt_me_route_drop_no_conn_total 794183
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1127147
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2135
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 1388
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 856
telemt_pool_swap_total 106
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18181
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17542
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 942778
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 15073601544 (14.04 GB)
telemt_user_octets_to_client{user="hello"} 412746212640 (384.40 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 66132.3 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 456377
telemt_connections_bad_total 45133
telemt_handshake_timeouts_total 11887
telemt_upstream_connect_attempt_total 24035
telemt_upstream_connect_success_total 23793
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 24035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 31952
telemt_me_reconnect_success_total 20341
telemt_me_reader_eof_total 21501
telemt_me_idle_close_by_peer_total 21501
telemt_me_seq_mismatch_total 32
telemt_me_route_drop_no_conn_total 111805
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330597
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1461
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 987
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 661
telemt_desync_frames_bucket_total{bucket="gt_10"} 559
telemt_pool_swap_total 44
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20923
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20299
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 330390
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 22907584969 (21.33 GB)
telemt_user_octets_to_client{user="hello"} 274835963858 (255.96 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 57
```