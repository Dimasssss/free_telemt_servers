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

# Server Metrics 2026-03-15 19:34:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 76771.8 (21h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360982
telemt_connections_bad_total 4408
telemt_handshake_timeouts_total 13538
telemt_upstream_connect_attempt_total 18485
telemt_upstream_connect_success_total 18392
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 18485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10202
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17951
telemt_me_reconnect_success_total 14551
telemt_me_reader_eof_total 15515
telemt_me_idle_close_by_peer_total 15515
telemt_me_route_drop_no_conn_total 473543
telemt_me_route_drop_channel_closed_total 77
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390361
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1934
telemt_desync_full_logged_total 759
telemt_desync_suppressed_total 1175
telemt_desync_frames_bucket_total{bucket="1_2"} 366
telemt_desync_frames_bucket_total{bucket="3_10"} 750
telemt_desync_frames_bucket_total{bucket="gt_10"} 818
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 14816
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 14517
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 329422
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 7448357424 (6.94 GB)
telemt_user_octets_to_client{user="hello"} 253069624768 (235.69 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 76779.4 (21h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147284
telemt_connections_bad_total 2845
telemt_handshake_timeouts_total 12850
telemt_upstream_connect_attempt_total 20924
telemt_upstream_connect_success_total 20901
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 20924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 464
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 938
telemt_me_reconnect_attempts_total 19203
telemt_me_reconnect_success_total 16785
telemt_me_reader_eof_total 17929
telemt_me_idle_close_by_peer_total 17928
telemt_me_route_drop_no_conn_total 61951
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125525
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
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 17103
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 16769
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 125706
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 2363843860 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 61687521077 (57.45 GB)
telemt_user_msgs_from_client{user="hello"} 561
telemt_user_msgs_to_client{user="hello"} 1281
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 76771.6 (21h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149018
telemt_connections_bad_total 1712
telemt_handshake_timeouts_total 3360
telemt_upstream_connect_attempt_total 22179
telemt_upstream_connect_success_total 22171
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 22179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 25637
telemt_me_reconnect_success_total 18273
telemt_me_reader_eof_total 19623
telemt_me_idle_close_by_peer_total 19623
telemt_me_route_drop_no_conn_total 58423
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131732
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 18685
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 18265
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 412
telemt_user_connections_total{user="hello"} 131619
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 10835555212 (10.09 GB)
telemt_user_octets_to_client{user="hello"} 72354733876 (67.39 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 76771.5 (21h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211756
telemt_connections_bad_total 1126
telemt_handshake_timeouts_total 1524
telemt_upstream_connect_attempt_total 18056
telemt_upstream_connect_success_total 18042
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 18056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 14290
telemt_me_reconnect_success_total 14204
telemt_me_reader_eof_total 15127
telemt_me_idle_close_by_peer_total 15127
telemt_me_route_drop_no_conn_total 78266
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194999
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 708
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 447
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 324
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 14372
telemt_me_writer_restored_same_endpoint_total 14193
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 194917
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 3670293536 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 89959097316 (83.78 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 51842.9 (14h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126953
telemt_connections_bad_total 25361
telemt_handshake_timeouts_total 2501
telemt_upstream_connect_attempt_total 15288
telemt_upstream_connect_success_total 15194
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 15288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 106873
telemt_me_reconnect_success_total 12424
telemt_me_reader_eof_total 13060
telemt_me_idle_close_by_peer_total 13060
telemt_me_route_drop_no_conn_total 43561
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95579
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 300
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 236
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 12506
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 12320
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 95709
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 1566197725 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 36392937319 (33.89 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 76771.0 (21h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519497
telemt_connections_bad_total 58012
telemt_handshake_timeouts_total 4211
telemt_upstream_connect_attempt_total 16392
telemt_upstream_connect_success_total 16299
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8433
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13740
telemt_me_reconnect_success_total 12430
telemt_me_reader_eof_total 13213
telemt_me_idle_close_by_peer_total 13213
telemt_me_route_drop_no_conn_total 342399
telemt_me_route_drop_channel_closed_total 90
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 486695
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 322
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 12605
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 12403
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 438065
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 11178463480 (10.41 GB)
telemt_user_octets_to_client{user="hello"} 245237105404 (228.39 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 62
```