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

# Server Metrics 2026-03-15 12:45:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 52271.8 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229592
telemt_connections_bad_total 1897
telemt_handshake_timeouts_total 4791
telemt_upstream_connect_attempt_total 13222
telemt_upstream_connect_success_total 13152
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13898
telemt_me_reconnect_success_total 10526
telemt_me_reader_eof_total 11247
telemt_me_idle_close_by_peer_total 11247
telemt_me_route_drop_no_conn_total 427595
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275203
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1569
telemt_desync_full_logged_total 626
telemt_desync_suppressed_total 943
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 629
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10738
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10495
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 214312
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 4318391736 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 196902148224 (183.38 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 52279.3 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82411
telemt_connections_bad_total 2705
telemt_handshake_timeouts_total 6885
telemt_upstream_connect_attempt_total 14424
telemt_upstream_connect_success_total 14424
telemt_upstream_connect_attempts_per_request{bucket="1"} 14424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 14107
telemt_me_reconnect_success_total 11769
telemt_me_reader_eof_total 12579
telemt_me_idle_close_by_peer_total 12579
telemt_me_route_drop_no_conn_total 36133
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70267
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 11969
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 11753
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 70264
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 1433657940 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 33923541244 (31.59 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 52271.7 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85224
telemt_connections_bad_total 1034
telemt_handshake_timeouts_total 2640
telemt_upstream_connect_attempt_total 15233
telemt_upstream_connect_success_total 15225
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 15233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 14715
telemt_me_reconnect_success_total 12570
telemt_me_reader_eof_total 13453
telemt_me_idle_close_by_peer_total 13453
telemt_me_route_drop_no_conn_total 32898
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77841
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 12757
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 12562
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 77757
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 9600318896 (8.94 GB)
telemt_user_octets_to_client{user="hello"} 46641850816 (43.44 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 52271.4 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116702
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 761
telemt_upstream_connect_attempt_total 12256
telemt_upstream_connect_success_total 12254
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9683
telemt_me_reconnect_success_total 9629
telemt_me_reader_eof_total 10273
telemt_me_idle_close_by_peer_total 10273
telemt_me_route_drop_no_conn_total 46276
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106414
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 288
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9737
telemt_me_writer_restored_same_endpoint_total 9618
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 106334
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 1898993564 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 57069831996 (53.15 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 27342.8 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62688
telemt_connections_bad_total 16038
telemt_handshake_timeouts_total 875
telemt_upstream_connect_attempt_total 8749
telemt_upstream_connect_success_total 8688
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 8749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 101547
telemt_me_reconnect_success_total 7127
telemt_me_reader_eof_total 7437
telemt_me_idle_close_by_peer_total 7437
telemt_me_route_drop_no_conn_total 21945
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44329
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7120
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 7023
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 44464
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 669744701 (638.72 MB)
telemt_user_octets_to_client{user="hello"} 17404046887 (16.21 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 52270.6 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303300
telemt_connections_bad_total 47765
telemt_handshake_timeouts_total 2465
telemt_upstream_connect_attempt_total 11052
telemt_upstream_connect_success_total 10985
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 11052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 8418
telemt_me_reconnect_success_total 8362
telemt_me_reader_eof_total 8901
telemt_me_idle_close_by_peer_total 8901
telemt_me_route_drop_no_conn_total 135102
telemt_me_route_drop_channel_closed_total 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244103
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 186
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8435
telemt_me_writer_restored_same_endpoint_total 8335
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 242465
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 5066132972 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 116233646156 (108.25 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 71
```