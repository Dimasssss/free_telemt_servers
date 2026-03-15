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

# Server Metrics 2026-03-15 18:12:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 71875.5 (19h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337600
telemt_connections_bad_total 4189
telemt_handshake_timeouts_total 10920
telemt_upstream_connect_attempt_total 17420
telemt_upstream_connect_success_total 17333
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 17420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17152
telemt_me_reconnect_success_total 13754
telemt_me_reader_eof_total 14649
telemt_me_idle_close_by_peer_total 14649
telemt_me_route_drop_no_conn_total 463333
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370482
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1870
telemt_desync_full_logged_total 742
telemt_desync_suppressed_total 1128
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 786
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 14008
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13720
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 309582
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 6331169852 (5.90 GB)
telemt_user_octets_to_client{user="hello"} 243002084844 (226.31 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 71882.9 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135123
telemt_connections_bad_total 2834
telemt_handshake_timeouts_total 12260
telemt_upstream_connect_attempt_total 19465
telemt_upstream_connect_success_total 19465
telemt_upstream_connect_attempts_per_request{bucket="1"} 19465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 315
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 18211
telemt_me_reconnect_success_total 15845
telemt_me_reader_eof_total 16938
telemt_me_idle_close_by_peer_total 16937
telemt_me_route_drop_no_conn_total 56099
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114491
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
telemt_me_writer_removed_unexpected_total 16126
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15829
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 114471
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 2138186900 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 56960740628 (53.05 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 71874.3 (19h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139285
telemt_connections_bad_total 1699
telemt_handshake_timeouts_total 3285
telemt_upstream_connect_attempt_total 21007
telemt_upstream_connect_success_total 20999
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 21007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24723
telemt_me_reconnect_success_total 17365
telemt_me_reader_eof_total 18636
telemt_me_idle_close_by_peer_total 18636
telemt_me_route_drop_no_conn_total 54450
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122503
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
telemt_me_writer_removed_unexpected_total 17762
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 17357
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 397
telemt_user_connections_total{user="hello"} 122395
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 10728763332 (9.99 GB)
telemt_user_octets_to_client{user="hello"} 68513899416 (63.81 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 71874.0 (19h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191101
telemt_connections_bad_total 962
telemt_handshake_timeouts_total 1284
telemt_upstream_connect_attempt_total 17012
telemt_upstream_connect_success_total 17000
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 17012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8795
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13506
telemt_me_reconnect_success_total 13423
telemt_me_reader_eof_total 14284
telemt_me_idle_close_by_peer_total 14284
telemt_me_route_drop_no_conn_total 72395
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176127
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 618
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 388
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13586
telemt_me_writer_restored_same_endpoint_total 13412
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 176039
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 3263331472 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 79969108200 (74.48 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 46945.6 (13h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115503
telemt_connections_bad_total 23948
telemt_handshake_timeouts_total 2463
telemt_upstream_connect_attempt_total 14004
telemt_upstream_connect_success_total 13921
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 14004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105816
telemt_me_reconnect_success_total 11371
telemt_me_reader_eof_total 11941
telemt_me_idle_close_by_peer_total 11941
telemt_me_route_drop_no_conn_total 39562
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85907
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
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 11437
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 11267
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 86039
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 1460909873 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 33673008923 (31.36 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 71873.9 (19h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 483454
telemt_connections_bad_total 57807
telemt_handshake_timeouts_total 3964
telemt_upstream_connect_attempt_total 15486
telemt_upstream_connect_success_total 15395
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 15486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13094
telemt_me_reconnect_success_total 11789
telemt_me_reader_eof_total 12521
telemt_me_idle_close_by_peer_total 12521
telemt_me_route_drop_no_conn_total 310648
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445336
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
telemt_me_writer_removed_unexpected_total 11954
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11762
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 403919
telemt_user_connections_current{user="hello"} 638
telemt_user_octets_from_client{user="hello"} 10479039760 (9.76 GB)
telemt_user_octets_to_client{user="hello"} 218088745600 (203.11 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 85
```