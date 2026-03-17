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

# Server Metrics 2026-03-17 06:50:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 43478.6 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266868
telemt_connections_bad_total 3388
telemt_handshake_timeouts_total 8451
telemt_upstream_connect_attempt_total 9049
telemt_upstream_connect_success_total 9001
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 9049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6853
telemt_me_reconnect_success_total 6828
telemt_me_reader_eof_total 7272
telemt_me_idle_close_by_peer_total 7272
telemt_me_route_drop_no_conn_total 81362
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239046
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1748
telemt_desync_full_logged_total 539
telemt_desync_suppressed_total 1209
telemt_desync_frames_bucket_total{bucket="1_2"} 406
telemt_desync_frames_bucket_total{bucket="3_10"} 877
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 6899
telemt_me_writer_restored_same_endpoint_total 6807
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 238832
telemt_user_connections_current{user="hello"} 638
telemt_user_octets_from_client{user="hello"} 3137563560 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 105346096668 (98.11 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 43730.3 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149232
telemt_connections_bad_total 2209
telemt_handshake_timeouts_total 11325
telemt_upstream_connect_attempt_total 12044
telemt_upstream_connect_success_total 11894
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 12044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_reconnect_attempts_total 10905
telemt_me_reconnect_success_total 9726
telemt_me_reader_eof_total 10273
telemt_me_idle_close_by_peer_total 10273
telemt_me_route_drop_no_conn_total 54998
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129754
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 359
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 230
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 99
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 9851
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9710
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 129777
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 1599292656 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 55823611648 (51.99 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 43506.2 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89362
telemt_connections_bad_total 1117
telemt_handshake_timeouts_total 2874
telemt_upstream_connect_attempt_total 11617
telemt_upstream_connect_success_total 11557
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 11617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6374
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9413
telemt_me_reconnect_success_total 9360
telemt_me_reader_eof_total 10022
telemt_me_idle_close_by_peer_total 10022
telemt_me_route_drop_no_conn_total 30035
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77054
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 57
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9473
telemt_me_writer_restored_same_endpoint_total 9349
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 77036
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 6170292448 (5.75 GB)
telemt_user_octets_to_client{user="hello"} 24696570128 (23.00 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 43565.3 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163434
telemt_connections_bad_total 5802
telemt_handshake_timeouts_total 8507
telemt_upstream_connect_attempt_total 9935
telemt_upstream_connect_success_total 9851
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 9935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_reconnect_attempts_total 7676
telemt_me_reconnect_success_total 7615
telemt_me_reader_eof_total 8088
telemt_me_idle_close_by_peer_total 8088
telemt_me_route_drop_no_conn_total 52864
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143838
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 269
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 187
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7723
telemt_me_writer_restored_same_endpoint_total 7608
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 143848
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 1563889246 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 69010688485 (64.27 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 43537.2 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120810
telemt_connections_bad_total 35924
telemt_handshake_timeouts_total 2374
telemt_upstream_connect_attempt_total 13279
telemt_upstream_connect_success_total 13105
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 13279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_reconnect_attempts_total 14072
telemt_me_reconnect_success_total 10812
telemt_me_reader_eof_total 11431
telemt_me_idle_close_by_peer_total 11431
telemt_me_route_drop_no_conn_total 31641
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79282
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 11053
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 10804
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 79329
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 812882375 (775.23 MB)
telemt_user_octets_to_client{user="hello"} 36449071914 (33.95 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 43698.8 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287503
telemt_connections_bad_total 41232
telemt_handshake_timeouts_total 2300
telemt_upstream_connect_attempt_total 8869
telemt_upstream_connect_success_total 8823
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4588
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6680
telemt_me_reconnect_success_total 6650
telemt_me_reader_eof_total 7129
telemt_me_idle_close_by_peer_total 7129
telemt_me_route_drop_no_conn_total 226524
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310851
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 289
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 6749
telemt_me_writer_restored_same_endpoint_total 6640
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 232787
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 3395305540 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 157351097124 (146.54 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 31704.8 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1310
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 15777
telemt_upstream_connect_success_total 15777
telemt_upstream_connect_attempts_per_request{bucket="1"} 15777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 14190
telemt_me_reconnect_success_total 14113
telemt_me_reader_eof_total 15445
telemt_me_idle_close_by_peer_total 15445
telemt_me_route_drop_no_conn_total 135
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1102
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 14241
telemt_me_writer_restored_same_endpoint_total 14113
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 1102
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 203857900 (194.41 MB)
telemt_user_octets_to_client{user="hello"} 12961407360 (12.07 GB)
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```