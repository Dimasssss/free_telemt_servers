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

# Server Metrics 2026-03-15 18:07:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 71569.4 (19h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335871
telemt_connections_bad_total 4188
telemt_handshake_timeouts_total 10692
telemt_upstream_connect_attempt_total 17385
telemt_upstream_connect_success_total 17298
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 17385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9606
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17117
telemt_me_reconnect_success_total 13720
telemt_me_reader_eof_total 14613
telemt_me_idle_close_by_peer_total 14613
telemt_me_route_drop_no_conn_total 462760
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 369028
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1865
telemt_desync_full_logged_total 740
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 352
telemt_desync_frames_bucket_total{bucket="3_10"} 729
telemt_desync_frames_bucket_total{bucket="gt_10"} 784
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13972
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13686
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 308127
telemt_user_connections_current{user="hello"} 367
telemt_user_octets_from_client{user="hello"} 6316943332 (5.88 GB)
telemt_user_octets_to_client{user="hello"} 242050487536 (225.43 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 71576.0 (19h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134520
telemt_connections_bad_total 2834
telemt_handshake_timeouts_total 12213
telemt_upstream_connect_attempt_total 19431
telemt_upstream_connect_success_total 19431
telemt_upstream_connect_attempts_per_request{bucket="1"} 19431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 313
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 18177
telemt_me_reconnect_success_total 15811
telemt_me_reader_eof_total 16903
telemt_me_idle_close_by_peer_total 16902
telemt_me_route_drop_no_conn_total 55735
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113941
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 16091
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15795
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 113921
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 2133249932 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 56709220708 (52.81 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 71568.5 (19h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138669
telemt_connections_bad_total 1699
telemt_handshake_timeouts_total 3284
telemt_upstream_connect_attempt_total 20953
telemt_upstream_connect_success_total 20945
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 20953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24669
telemt_me_reconnect_success_total 17311
telemt_me_reader_eof_total 18580
telemt_me_idle_close_by_peer_total 18580
telemt_me_route_drop_no_conn_total 54240
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121907
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 17706
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 17303
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 395
telemt_user_connections_total{user="hello"} 121799
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 10723949168 (9.99 GB)
telemt_user_octets_to_client{user="hello"} 68306837480 (63.62 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 71568.3 (19h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189890
telemt_connections_bad_total 960
telemt_handshake_timeouts_total 1275
telemt_upstream_connect_attempt_total 16974
telemt_upstream_connect_success_total 16962
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 16974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8770
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13468
telemt_me_reconnect_success_total 13385
telemt_me_reader_eof_total 14245
telemt_me_idle_close_by_peer_total 14245
telemt_me_route_drop_no_conn_total 72040
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174972
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 614
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 387
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 284
telemt_desync_frames_bucket_total{bucket="gt_10"} 201
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13547
telemt_me_writer_restored_same_endpoint_total 13374
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 174884
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 3227719660 (3.01 GB)
telemt_user_octets_to_client{user="hello"} 79375785916 (73.92 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 46639.6 (12h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114783
telemt_connections_bad_total 23868
telemt_handshake_timeouts_total 2459
telemt_upstream_connect_attempt_total 13907
telemt_upstream_connect_success_total 13827
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 13907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105765
telemt_me_reconnect_success_total 11320
telemt_me_reader_eof_total 11884
telemt_me_idle_close_by_peer_total 11884
telemt_me_route_drop_no_conn_total 39398
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85284
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 263
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 208
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 11386
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 11216
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 85417
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 1456162425 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 33482988367 (31.18 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 71568.0 (19h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480552
telemt_connections_bad_total 57770
telemt_handshake_timeouts_total 3935
telemt_upstream_connect_attempt_total 15455
telemt_upstream_connect_success_total 15364
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 15455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7900
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13063
telemt_me_reconnect_success_total 11758
telemt_me_reader_eof_total 12490
telemt_me_idle_close_by_peer_total 12490
telemt_me_route_drop_no_conn_total 309140
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442623
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 11923
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11731
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 401206
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 10457954308 (9.74 GB)
telemt_user_octets_to_client{user="hello"} 216356168336 (201.50 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 86
```