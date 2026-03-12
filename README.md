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

# Server Metrics 2026-03-12 13:49:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 22574.9 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119772
telemt_connections_bad_total 1359
telemt_handshake_timeouts_total 4256
telemt_upstream_connect_attempt_total 5449
telemt_upstream_connect_success_total 5425
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 247
telemt_me_reconnect_attempts_total 4280
telemt_me_reconnect_success_total 4252
telemt_me_reader_eof_total 4459
telemt_me_idle_close_by_peer_total 4458
telemt_me_route_drop_no_conn_total 33550
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105209
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 317
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 214
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4286
telemt_me_writer_restored_same_endpoint_total 4236
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 105173
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 1703280844 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 40272781412 (37.51 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 22467.9 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48505
telemt_connections_bad_total 336
telemt_handshake_timeouts_total 346
telemt_upstream_connect_attempt_total 6619
telemt_upstream_connect_success_total 6463
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 6619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 21164
telemt_me_reconnect_success_total 5332
telemt_me_reader_eof_total 5923
telemt_me_idle_close_by_peer_total 5923
telemt_me_route_drop_no_conn_total 21529
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46331
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5857
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 5317
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 46328
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 559477768 (533.56 MB)
telemt_user_octets_to_client{user="hello"} 13371742696 (12.45 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 22431.3 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65922
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 782
telemt_upstream_connect_attempt_total 6084
telemt_upstream_connect_success_total 6084
telemt_upstream_connect_attempts_per_request{bucket="1"} 6084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 4959
telemt_me_reconnect_success_total 4921
telemt_me_reader_eof_total 5194
telemt_me_idle_close_by_peer_total 5194
telemt_me_route_drop_no_conn_total 23019
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62068
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4955
telemt_me_writer_restored_same_endpoint_total 4901
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 62050
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 1825469488 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 35810250888 (33.35 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 22407.1 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84960
telemt_connections_bad_total 1463
telemt_handshake_timeouts_total 395
telemt_upstream_connect_attempt_total 6060
telemt_upstream_connect_success_total 5909
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 6060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 235
telemt_me_reconnect_attempts_total 15178
telemt_me_reconnect_success_total 4759
telemt_me_reader_eof_total 5214
telemt_me_idle_close_by_peer_total 5214
telemt_me_route_drop_no_conn_total 31909
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78022
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 239
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5139
telemt_me_refill_failed_total 324
telemt_me_writer_restored_same_endpoint_total 4751
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 77906
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 1284525948 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 34485001452 (32.12 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 22376.5 (6h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49200
telemt_connections_bad_total 4209
telemt_handshake_timeouts_total 683
telemt_upstream_connect_attempt_total 16207
telemt_upstream_connect_success_total 15940
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 16207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 28688
telemt_me_reconnect_success_total 3670
telemt_me_reader_eof_total 4448
telemt_me_idle_close_by_peer_total 4448
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 11995
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31997
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 428
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 310
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4473
telemt_me_refill_failed_total 783
telemt_me_writer_restored_same_endpoint_total 3653
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 803
telemt_user_connections_total{user="hello"} 43120
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 353917257 (337.52 MB)
telemt_user_octets_to_client{user="hello"} 11174399023 (10.41 GB)
telemt_user_msgs_from_client{user="hello"} 158163
telemt_user_msgs_to_client{user="hello"} 459833
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 22363.5 (6h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132413
telemt_connections_bad_total 772
telemt_handshake_timeouts_total 995
telemt_upstream_connect_attempt_total 4578
telemt_upstream_connect_success_total 4555
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 3449
telemt_me_reconnect_success_total 3420
telemt_me_reader_eof_total 3604
telemt_me_idle_close_by_peer_total 3604
telemt_me_route_drop_no_conn_total 52960
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126438
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 222
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3462
telemt_me_writer_restored_same_endpoint_total 3413
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 126409
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 2744814180 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 53493443748 (49.82 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 59
```