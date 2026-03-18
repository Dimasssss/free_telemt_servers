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

# Server Metrics 2026-03-18 14:26:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 20720.2 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 768041
telemt_connections_bad_total 41117
telemt_handshake_timeouts_total 21036
telemt_upstream_connect_attempt_total 66960
telemt_upstream_connect_success_total 65997
telemt_upstream_connect_fail_total 963
telemt_upstream_connect_attempts_per_request{bucket="1"} 66960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 963
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 515786
telemt_me_reconnect_success_total 2979
telemt_me_reader_eof_total 3189
telemt_me_idle_close_by_peer_total 3187
telemt_me_route_drop_no_conn_total 434622
telemt_me_route_drop_channel_closed_total 169
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 596129
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2588
telemt_desync_full_logged_total 916
telemt_desync_suppressed_total 1672
telemt_desync_frames_bucket_total{bucket="1_2"} 714
telemt_desync_frames_bucket_total{bucket="3_10"} 888
telemt_desync_frames_bucket_total{bucket="gt_10"} 986
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3193
telemt_me_refill_failed_total 16708
telemt_me_writer_restored_same_endpoint_total 2874
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 654233
telemt_user_connections_current{user="hello"} 1635
telemt_user_octets_from_client{user="hello"} 9646304912 (8.98 GB)
telemt_user_octets_to_client{user="hello"} 170855112925 (159.12 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 537
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 1289.0 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132030
telemt_connections_bad_total 6441
telemt_connections_current 3932
telemt_connections_me_current 3932
telemt_handshake_timeouts_total 2634
telemt_upstream_connect_attempt_total 272
telemt_upstream_connect_success_total 270
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 159
telemt_me_reconnect_success_total 157
telemt_me_reader_eof_total 49
telemt_me_idle_close_by_peer_total 49
telemt_me_route_drop_no_conn_total 58605
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115598
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 347
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 235
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 127
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 71
telemt_me_writer_restored_same_endpoint_total 155
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 115364
telemt_user_connections_current{user="hello"} 3932
telemt_user_octets_from_client{user="hello"} 1402649116 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 39487992012 (36.78 GB)
telemt_user_unique_ips_current{user="hello"} 1230
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 1217.4 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93133
telemt_connections_bad_total 4300
telemt_connections_current 3103
telemt_connections_me_current 3103
telemt_handshake_timeouts_total 1550
telemt_upstream_connect_attempt_total 193
telemt_upstream_connect_success_total 191
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 79
telemt_me_reconnect_success_total 78
telemt_me_reader_eof_total 59
telemt_me_idle_close_by_peer_total 59
telemt_me_route_drop_no_conn_total 29296
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79932
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 234
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 79
telemt_me_writer_restored_same_endpoint_total 61
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 79913
telemt_user_connections_current{user="hello"} 3103
telemt_user_octets_from_client{user="hello"} 2178197840 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 30868967040 (28.75 GB)
telemt_user_unique_ips_current{user="hello"} 971
telemt_user_unique_ips_recent_window{user="hello"} 457
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 1931.6 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198458
telemt_connections_bad_total 670
telemt_connections_current 2576
telemt_connections_me_current 2576
telemt_handshake_timeouts_total 3756
telemt_upstream_connect_attempt_total 313
telemt_upstream_connect_success_total 311
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 166
telemt_me_reconnect_success_total 165
telemt_me_reader_eof_total 117
telemt_me_idle_close_by_peer_total 116
telemt_me_route_drop_no_conn_total 271078
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176590
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 366
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 137
telemt_me_writer_restored_same_endpoint_total 154
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 176569
telemt_user_connections_current{user="hello"} 2576
telemt_user_octets_from_client{user="hello"} 1009932584 (963.15 MB)
telemt_user_octets_to_client{user="hello"} 24933069048 (23.22 GB)
telemt_user_unique_ips_current{user="hello"} 791
telemt_user_unique_ips_recent_window{user="hello"} 387
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 20591.5 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1708274
telemt_connections_bad_total 133756
telemt_handshake_timeouts_total 27505
telemt_upstream_connect_attempt_total 15140
telemt_upstream_connect_success_total 15112
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 801
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986844
telemt_me_reconnect_success_total 2405
telemt_me_reader_eof_total 2513
telemt_me_idle_close_by_peer_total 2513
telemt_me_route_drop_no_conn_total 1844180
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1423439
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3979
telemt_desync_full_logged_total 1373
telemt_desync_suppressed_total 2606
telemt_desync_frames_bucket_total{bucket="1_2"} 659
telemt_desync_frames_bucket_total{bucket="3_10"} 1536
telemt_desync_frames_bucket_total{bucket="gt_10"} 1784
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2475
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2290
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1425283
telemt_user_connections_current{user="hello"} 3023
telemt_user_octets_from_client{user="hello"} 21087238011 (19.64 GB)
telemt_user_octets_to_client{user="hello"} 467431501133 (435.33 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 984
telemt_user_unique_ips_recent_window{user="hello"} 448
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 1380.4 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40930
telemt_connections_bad_total 3080
telemt_connections_current 835
telemt_connections_me_current 835
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 370
telemt_upstream_connect_attempt_total 4308
telemt_upstream_connect_success_total 4305
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1695
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 329824
telemt_me_reconnect_success_total 372
telemt_me_reader_eof_total 267
telemt_me_idle_close_by_peer_total 267
telemt_me_route_drop_no_conn_total 29049
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31747
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 74
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 284
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 361
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 35528
telemt_user_connections_current{user="hello"} 835
telemt_user_octets_from_client{user="hello"} 529501473 (504.97 MB)
telemt_user_octets_to_client{user="hello"} 4584794389 (4.27 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 450.8 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35824
telemt_connections_bad_total 142
telemt_connections_current 2477
telemt_connections_me_current 2477
telemt_handshake_timeouts_total 374
telemt_upstream_connect_attempt_total 235
telemt_upstream_connect_success_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 72
telemt_me_reconnect_attempts_total 14451
telemt_me_reconnect_success_total 163
telemt_me_reader_eof_total 41
telemt_me_idle_close_by_peer_total 41
telemt_me_route_drop_no_conn_total 25964
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32555
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 40
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_writer_removed_unexpected_total 63
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 102
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 32550
telemt_user_connections_current{user="hello"} 2477
telemt_user_octets_from_client{user="hello"} 476691612 (454.61 MB)
telemt_user_octets_to_client{user="hello"} 6713438564 (6.25 GB)
telemt_user_unique_ips_current{user="hello"} 807
telemt_user_unique_ips_recent_window{user="hello"} 416
```