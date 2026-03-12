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

# Server Metrics 2026-03-12 13:13:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 20432.3 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108195
telemt_connections_bad_total 546
telemt_handshake_timeouts_total 3721
telemt_upstream_connect_attempt_total 4987
telemt_upstream_connect_success_total 4964
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 208
telemt_me_reconnect_attempts_total 3932
telemt_me_reconnect_success_total 3906
telemt_me_reader_eof_total 4086
telemt_me_idle_close_by_peer_total 4085
telemt_me_route_drop_no_conn_total 30775
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96473
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 459
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 287
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3936
telemt_me_writer_restored_same_endpoint_total 3890
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 96438
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 1349979076 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 36038128844 (33.56 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 20325.2 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43988
telemt_connections_bad_total 335
telemt_handshake_timeouts_total 337
telemt_upstream_connect_attempt_total 6065
telemt_upstream_connect_success_total 5912
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 6065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 148
telemt_me_reconnect_attempts_total 20700
telemt_me_reconnect_success_total 4874
telemt_me_reader_eof_total 5428
telemt_me_idle_close_by_peer_total 5428
telemt_me_route_drop_no_conn_total 18857
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41932
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
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 5392
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 4859
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 518
telemt_user_connections_total{user="hello"} 41931
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 503323664 (480.01 MB)
telemt_user_octets_to_client{user="hello"} 11364653004 (10.58 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 20288.9 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59544
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 623
telemt_upstream_connect_attempt_total 5564
telemt_upstream_connect_success_total 5564
telemt_upstream_connect_attempts_per_request{bucket="1"} 5564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 4529
telemt_me_reconnect_success_total 4497
telemt_me_reader_eof_total 4737
telemt_me_idle_close_by_peer_total 4737
telemt_me_route_drop_no_conn_total 20723
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56062
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4525
telemt_me_writer_restored_same_endpoint_total 4477
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 56044
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 1776020152 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 33779643932 (31.46 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 20264.5 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76035
telemt_connections_bad_total 1095
telemt_handshake_timeouts_total 349
telemt_upstream_connect_attempt_total 5590
telemt_upstream_connect_success_total 5446
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 5590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3013
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 197
telemt_me_reconnect_attempts_total 12119
telemt_me_reconnect_success_total 4389
telemt_me_reader_eof_total 4759
telemt_me_idle_close_by_peer_total 4759
telemt_me_route_drop_no_conn_total 25633
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69818
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 210
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4683
telemt_me_refill_failed_total 240
telemt_me_writer_restored_same_endpoint_total 4381
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 69819
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 1188148456 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 32464432696 (30.23 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 20233.7 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43774
telemt_connections_bad_total 3825
telemt_handshake_timeouts_total 655
telemt_upstream_connect_attempt_total 11780
telemt_upstream_connect_success_total 11541
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 11780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 25893
telemt_me_reconnect_success_total 3629
telemt_me_reader_eof_total 4321
telemt_me_idle_close_by_peer_total 4321
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 11737
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31362
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 404
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 334
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4346
telemt_me_refill_failed_total 697
telemt_me_writer_restored_same_endpoint_total 3612
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 717
telemt_user_connections_total{user="hello"} 38217
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 294467105 (280.83 MB)
telemt_user_octets_to_client{user="hello"} 10144621128 (9.45 GB)
telemt_user_msgs_from_client{user="hello"} 92822
telemt_user_msgs_to_client{user="hello"} 308435
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 20220.6 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116487
telemt_connections_bad_total 767
telemt_handshake_timeouts_total 956
telemt_upstream_connect_attempt_total 4161
telemt_upstream_connect_success_total 4139
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 4161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 3121
telemt_me_reconnect_success_total 3093
telemt_me_reader_eof_total 3252
telemt_me_idle_close_by_peer_total 3252
telemt_me_route_drop_no_conn_total 47500
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110925
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 213
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3132
telemt_me_writer_restored_same_endpoint_total 3086
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 110890
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 2614339840 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 49799819244 (46.38 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 55
```