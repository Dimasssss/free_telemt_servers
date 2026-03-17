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

# Server Metrics 2026-03-17 06:24:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 41951.9 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246005
telemt_connections_bad_total 3355
telemt_handshake_timeouts_total 8070
telemt_upstream_connect_attempt_total 8759
telemt_upstream_connect_success_total 8713
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6652
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7055
telemt_me_idle_close_by_peer_total 7055
telemt_me_route_drop_no_conn_total 76477
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222650
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1639
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 369
telemt_desync_frames_bucket_total{bucket="3_10"} 842
telemt_desync_frames_bucket_total{bucket="gt_10"} 428
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6695
telemt_me_writer_restored_same_endpoint_total 6606
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 222439
telemt_user_connections_current{user="hello"} 632
telemt_user_octets_from_client{user="hello"} 3032274036 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 97569218904 (90.87 GB)
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 42203.1 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139979
telemt_connections_bad_total 2207
telemt_handshake_timeouts_total 10628
telemt_upstream_connect_attempt_total 11531
telemt_upstream_connect_success_total 11384
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 11531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_reconnect_attempts_total 10485
telemt_me_reconnect_success_total 9309
telemt_me_reader_eof_total 9852
telemt_me_idle_close_by_peer_total 9852
telemt_me_route_drop_no_conn_total 52549
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122053
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 325
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 9430
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9293
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 122062
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 1493380100 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 51866203548 (48.30 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 41979.2 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83631
telemt_connections_bad_total 1110
telemt_handshake_timeouts_total 2698
telemt_upstream_connect_attempt_total 11298
telemt_upstream_connect_success_total 11239
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 11298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9183
telemt_me_reconnect_success_total 9134
telemt_me_reader_eof_total 9776
telemt_me_idle_close_by_peer_total 9776
telemt_me_route_drop_no_conn_total 28688
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72132
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9243
telemt_me_writer_restored_same_endpoint_total 9123
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 72115
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 6106141956 (5.69 GB)
telemt_user_octets_to_client{user="hello"} 23439611536 (21.83 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 42038.4 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147827
telemt_connections_bad_total 3789
telemt_handshake_timeouts_total 6062
telemt_upstream_connect_attempt_total 9490
telemt_upstream_connect_success_total 9409
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 9490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_reconnect_attempts_total 7323
telemt_me_reconnect_success_total 7267
telemt_me_reader_eof_total 7738
telemt_me_idle_close_by_peer_total 7738
telemt_me_route_drop_no_conn_total 49037
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133599
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 244
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7373
telemt_me_writer_restored_same_endpoint_total 7260
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 133616
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 1464160898 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 65036996133 (60.57 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 42010.3 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112627
telemt_connections_bad_total 32982
telemt_handshake_timeouts_total 2367
telemt_upstream_connect_attempt_total 12677
telemt_upstream_connect_success_total 12508
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 12677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_reconnect_attempts_total 12570
telemt_me_reconnect_success_total 10304
telemt_me_reader_eof_total 10862
telemt_me_idle_close_by_peer_total 10862
telemt_me_route_drop_no_conn_total 28614
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74163
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 40
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 10507
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 10296
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 74260
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 786328831 (749.90 MB)
telemt_user_octets_to_client{user="hello"} 32634822434 (30.39 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 42171.6 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270085
telemt_connections_bad_total 37544
telemt_handshake_timeouts_total 2156
telemt_upstream_connect_attempt_total 8594
telemt_upstream_connect_success_total 8549
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 8594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6494
telemt_me_reconnect_success_total 6465
telemt_me_reader_eof_total 6932
telemt_me_idle_close_by_peer_total 6932
telemt_me_route_drop_no_conn_total 220834
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298492
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 257
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 130
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 6562
telemt_me_writer_restored_same_endpoint_total 6455
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 220432
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 3302868100 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 153696038820 (143.14 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 30177.7 (8h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 929
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 14946
telemt_upstream_connect_success_total 14946
telemt_upstream_connect_attempts_per_request{bucket="1"} 14946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 13446
telemt_me_reconnect_success_total 13372
telemt_me_reader_eof_total 14643
telemt_me_idle_close_by_peer_total 14643
telemt_me_route_drop_no_conn_total 106
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 730
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 13493
telemt_me_writer_restored_same_endpoint_total 13372
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 730
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 196871220 (187.75 MB)
telemt_user_octets_to_client{user="hello"} 11735258804 (10.93 GB)
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```