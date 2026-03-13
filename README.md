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

# Server Metrics 2026-03-13 05:45:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 79952.8 (22h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303367
telemt_connections_bad_total 3074
telemt_handshake_timeouts_total 6217
telemt_upstream_connect_attempt_total 20087
telemt_upstream_connect_success_total 19993
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 20087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1578
telemt_me_reconnect_attempts_total 19486
telemt_me_reconnect_success_total 15988
telemt_me_reader_eof_total 17097
telemt_me_idle_close_by_peer_total 17096
telemt_me_route_drop_no_conn_total 94633
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255785
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 879
telemt_desync_full_logged_total 326
telemt_desync_suppressed_total 553
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 321
telemt_desync_frames_bucket_total{bucket="gt_10"} 383
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 16270
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15972
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 255721
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 4363091000 (4.06 GB)
telemt_user_octets_to_client{user="hello"} 123872596800 (115.37 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 79845.9 (22h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138443
telemt_connections_bad_total 762
telemt_handshake_timeouts_total 1041
telemt_upstream_connect_attempt_total 42266
telemt_upstream_connect_success_total 41729
telemt_upstream_connect_fail_total 537
telemt_upstream_connect_attempts_per_request{bucket="1"} 42266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 508
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 537
telemt_me_keepalive_timeout_total 592
telemt_me_reconnect_attempts_total 67807
telemt_me_reconnect_success_total 21243
telemt_me_reader_eof_total 23347
telemt_me_idle_close_by_peer_total 23347
telemt_me_route_drop_no_conn_total 51535
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115069
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
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
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 22862
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 21228
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1619
telemt_user_connections_total{user="hello"} 131567
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 1362653304 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 39795665883 (37.06 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 79809.6 (22h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167790
telemt_connections_bad_total 1884
telemt_handshake_timeouts_total 2705
telemt_upstream_connect_attempt_total 21982
telemt_upstream_connect_success_total 21980
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 21982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11848
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 465
telemt_me_reconnect_attempts_total 19123
telemt_me_reconnect_success_total 17955
telemt_me_reader_eof_total 19242
telemt_me_idle_close_by_peer_total 19242
telemt_me_route_drop_no_conn_total 65003
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156934
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 18151
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17935
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 156862
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 2922938616 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 71756815168 (66.83 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 79785.1 (22h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242209
telemt_connections_bad_total 13565
telemt_handshake_timeouts_total 1804
telemt_upstream_connect_attempt_total 34149
telemt_upstream_connect_success_total 24245
telemt_upstream_connect_fail_total 9904
telemt_upstream_connect_attempts_per_request{bucket="1"} 34149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11856
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9904
telemt_me_keepalive_timeout_total 3317
telemt_me_reconnect_attempts_total 68933
telemt_me_reconnect_success_total 17401
telemt_me_reader_eof_total 19543
telemt_me_idle_close_by_peer_total 19536
telemt_me_route_drop_no_conn_total 88531
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203262
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 578
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 411
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 19236
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 17391
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1835
telemt_user_connections_total{user="hello"} 206005
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 3304338174 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 81550812305 (75.95 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 29956.8 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32021
telemt_connections_bad_total 5623
telemt_handshake_timeouts_total 137
telemt_upstream_connect_attempt_total 10048
telemt_upstream_connect_success_total 9947
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 10048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 241
telemt_me_reconnect_attempts_total 9386
telemt_me_reconnect_success_total 8426
telemt_me_reader_eof_total 8994
telemt_me_idle_close_by_peer_total 8994
telemt_me_route_drop_no_conn_total 9075
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25403
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 8535
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 8408
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 25403
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 201521696 (192.19 MB)
telemt_user_octets_to_client{user="hello"} 9474193928 (8.82 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 79741.7 (22h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 409000
telemt_connections_bad_total 7929
telemt_handshake_timeouts_total 3064
telemt_upstream_connect_attempt_total 16997
telemt_upstream_connect_success_total 16903
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 16997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 1451
telemt_me_reconnect_attempts_total 16570
telemt_me_reconnect_success_total 12938
telemt_me_reader_eof_total 13894
telemt_me_idle_close_by_peer_total 13891
telemt_me_route_drop_no_conn_total 181569
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 396988
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 343
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 13215
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12931
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 385235
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 6354641168 (5.92 GB)
telemt_user_octets_to_client{user="hello"} 226832606844 (211.25 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 56
```