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

# Server Metrics 2026-03-13 08:55:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 91321.0 (25h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356292
telemt_connections_bad_total 3179
telemt_handshake_timeouts_total 7768
telemt_upstream_connect_attempt_total 23004
telemt_upstream_connect_success_total 22895
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 23004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12524
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1676
telemt_me_reconnect_attempts_total 21816
telemt_me_reconnect_success_total 18306
telemt_me_reader_eof_total 19548
telemt_me_idle_close_by_peer_total 19547
telemt_me_route_drop_no_conn_total 112208
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304573
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 981
telemt_desync_full_logged_total 365
telemt_desync_suppressed_total 616
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 422
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 18605
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 18290
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 304265
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 4977924168 (4.64 GB)
telemt_user_octets_to_client{user="hello"} 137995729512 (128.52 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 91214.0 (25h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162007
telemt_connections_bad_total 1510
telemt_handshake_timeouts_total 1223
telemt_upstream_connect_attempt_total 45807
telemt_upstream_connect_success_total 45185
telemt_upstream_connect_fail_total 622
telemt_upstream_connect_attempts_per_request{bucket="1"} 45807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 514
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 622
telemt_me_keepalive_timeout_total 702
telemt_me_reconnect_attempts_total 79497
telemt_me_reconnect_success_total 24125
telemt_me_reader_eof_total 26585
telemt_me_idle_close_by_peer_total 26585
telemt_me_route_drop_no_conn_total 61856
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136315
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 19
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
telemt_me_writer_removed_unexpected_total 26051
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 24110
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1926
telemt_user_connections_total{user="hello"} 152807
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 1576147644 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 49053466839 (45.68 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 91177.4 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196515
telemt_connections_bad_total 1999
telemt_handshake_timeouts_total 3714
telemt_upstream_connect_attempt_total 24754
telemt_upstream_connect_success_total 24751
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13362
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 584
telemt_me_reconnect_attempts_total 21328
telemt_me_reconnect_success_total 20143
telemt_me_reader_eof_total 21607
telemt_me_idle_close_by_peer_total 21607
telemt_me_route_drop_no_conn_total 74803
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183597
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
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 20365
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20123
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 183526
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 6740630912 (6.28 GB)
telemt_user_octets_to_client{user="hello"} 76597028992 (71.34 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 91153.0 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283338
telemt_connections_bad_total 13662
telemt_handshake_timeouts_total 2123
telemt_upstream_connect_attempt_total 37767
telemt_upstream_connect_success_total 27780
telemt_upstream_connect_fail_total 9987
telemt_upstream_connect_attempts_per_request{bucket="1"} 37767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13749
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9987
telemt_me_keepalive_timeout_total 3390
telemt_me_reconnect_attempts_total 74269
telemt_me_reconnect_success_total 20355
telemt_me_reader_eof_total 22678
telemt_me_idle_close_by_peer_total 22671
telemt_me_route_drop_no_conn_total 102317
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 241413
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 890
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 627
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 329
telemt_desync_frames_bucket_total{bucket="gt_10"} 335
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 22300
telemt_me_refill_failed_total 1680
telemt_me_writer_restored_same_endpoint_total 20345
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1945
telemt_user_connections_total{user="hello"} 244138
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 5483685742 (5.11 GB)
telemt_user_octets_to_client{user="hello"} 93053508321 (86.66 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 41324.8 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52733
telemt_connections_bad_total 8368
telemt_handshake_timeouts_total 448
telemt_upstream_connect_attempt_total 14302
telemt_upstream_connect_success_total 14158
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 14302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 345
telemt_me_reconnect_attempts_total 14321
telemt_me_reconnect_success_total 12101
telemt_me_reader_eof_total 12892
telemt_me_idle_close_by_peer_total 12892
telemt_me_route_drop_no_conn_total 15930
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42470
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 12274
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 12083
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 42468
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 310466176 (296.08 MB)
telemt_user_octets_to_client{user="hello"} 11742274932 (10.94 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 91109.6 (25h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 486858
telemt_connections_bad_total 13394
telemt_handshake_timeouts_total 4673
telemt_upstream_connect_attempt_total 19267
telemt_upstream_connect_success_total 19164
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 19267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 1539
telemt_me_reconnect_attempts_total 18268
telemt_me_reconnect_success_total 14623
telemt_me_reader_eof_total 15712
telemt_me_idle_close_by_peer_total 15709
telemt_me_route_drop_no_conn_total 255080
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 478452
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 396
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 14925
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14616
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 451547
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 8314730928 (7.74 GB)
telemt_user_octets_to_client{user="hello"} 256874026816 (239.23 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 61
```