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

# Server Metrics 2026-03-13 14:39:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 111973.5 (31h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 463382
telemt_connections_bad_total 3217
telemt_handshake_timeouts_total 8619
telemt_upstream_connect_attempt_total 28162
telemt_upstream_connect_success_total 28028
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 28162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2428
telemt_me_reconnect_attempts_total 25948
telemt_me_reconnect_success_total 22417
telemt_me_reader_eof_total 23947
telemt_me_idle_close_by_peer_total 23946
telemt_me_route_drop_no_conn_total 150663
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 405846
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1342
telemt_desync_full_logged_total 475
telemt_desync_suppressed_total 867
telemt_desync_frames_bucket_total{bucket="1_2"} 291
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 564
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 22761
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22401
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 344
telemt_user_connections_total{user="hello"} 405423
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 7322718196 (6.82 GB)
telemt_user_octets_to_client{user="hello"} 187081232904 (174.23 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 111866.8 (31h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219978
telemt_connections_bad_total 1830
telemt_handshake_timeouts_total 1552
telemt_upstream_connect_attempt_total 78178
telemt_upstream_connect_success_total 77425
telemt_upstream_connect_fail_total 753
telemt_upstream_connect_attempts_per_request{bucket="1"} 78178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 757
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 753
telemt_me_keepalive_timeout_total 1397
telemt_me_reconnect_attempts_total 109426
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29388
telemt_me_idle_close_by_peer_total 29388
telemt_me_route_drop_no_conn_total 80234
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162283
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28852
telemt_me_refill_failed_total 2602
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2830
telemt_user_connections_total{user="hello"} 207869
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 2092925898 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 66316919011 (61.76 GB)
telemt_user_msgs_from_client{user="hello"} 670854
telemt_user_msgs_to_client{user="hello"} 4515823
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 111830.6 (31h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266273
telemt_connections_bad_total 2196
telemt_handshake_timeouts_total 11508
telemt_upstream_connect_attempt_total 30155
telemt_upstream_connect_success_total 30151
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 30155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2289
telemt_me_reconnect_attempts_total 25718
telemt_me_reconnect_success_total 24501
telemt_me_reader_eof_total 26253
telemt_me_idle_close_by_peer_total 26253
telemt_me_route_drop_no_conn_total 96482
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243024
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 24769
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 24481
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 242939
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 9517496492 (8.86 GB)
telemt_user_octets_to_client{user="hello"} 105005834868 (97.79 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 111805.9 (31h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365228
telemt_connections_bad_total 15044
telemt_handshake_timeouts_total 3631
telemt_upstream_connect_attempt_total 42140
telemt_upstream_connect_success_total 31997
telemt_upstream_connect_fail_total 10142
telemt_upstream_connect_attempts_per_request{bucket="1"} 42139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10142
telemt_me_keepalive_timeout_total 4144
telemt_me_reconnect_attempts_total 97749
telemt_me_reconnect_success_total 23342
telemt_me_reader_eof_total 26370
telemt_me_idle_close_by_peer_total 26363
telemt_me_route_drop_no_conn_total 130891
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315673
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1224
telemt_desync_full_logged_total 361
telemt_desync_suppressed_total 863
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 459
telemt_desync_frames_bucket_total{bucket="gt_10"} 462
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 25968
telemt_me_refill_failed_total 2320
telemt_me_writer_restored_same_endpoint_total 23332
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2626
telemt_user_connections_total{user="hello"} 318583
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 6838875362 (6.37 GB)
telemt_user_octets_to_client{user="hello"} 120141489265 (111.89 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 61977.5 (17h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95140
telemt_connections_bad_total 12459
telemt_handshake_timeouts_total 1216
telemt_upstream_connect_attempt_total 25468
telemt_upstream_connect_success_total 25260
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 25468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 1033
telemt_me_reconnect_attempts_total 27181
telemt_me_reconnect_success_total 17258
telemt_me_reader_eof_total 18514
telemt_me_idle_close_by_peer_total 18514
telemt_me_route_drop_no_conn_total 28283
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73525
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 316
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 253
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 17718
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 17240
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 78425
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 919588329 (876.99 MB)
telemt_user_octets_to_client{user="hello"} 22787159587 (21.22 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 111762.4 (31h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 660987
telemt_connections_bad_total 18506
telemt_handshake_timeouts_total 20572
telemt_upstream_connect_attempt_total 23500
telemt_upstream_connect_success_total 23382
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 23500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2531
telemt_me_reconnect_attempts_total 22434
telemt_me_reconnect_success_total 17809
telemt_me_reader_eof_total 19118
telemt_me_idle_close_by_peer_total 19115
telemt_me_route_drop_no_conn_total 318042
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 626766
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 481
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 18184
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17802
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 599715
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 10342528356 (9.63 GB)
telemt_user_octets_to_client{user="hello"} 312885080068 (291.40 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 71
```