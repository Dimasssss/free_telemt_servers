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

# Server Metrics 2026-03-13 00:44:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 61840.0 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258754
telemt_connections_bad_total 2764
telemt_handshake_timeouts_total 5394
telemt_upstream_connect_attempt_total 15577
telemt_upstream_connect_success_total 15509
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 15577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1497
telemt_me_reconnect_attempts_total 15865
telemt_me_reconnect_success_total 12392
telemt_me_reader_eof_total 13213
telemt_me_idle_close_by_peer_total 13212
telemt_me_route_drop_no_conn_total 80385
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214135
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 725
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 327
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12637
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 12376
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 213903
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 3907143816 (3.64 GB)
telemt_user_octets_to_client{user="hello"} 108756453528 (101.29 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 61732.7 (17h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119750
telemt_connections_bad_total 711
telemt_handshake_timeouts_total 969
telemt_upstream_connect_attempt_total 35026
telemt_upstream_connect_success_total 34610
telemt_upstream_connect_fail_total 416
telemt_upstream_connect_attempts_per_request{bucket="1"} 35026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 416
telemt_me_keepalive_timeout_total 436
telemt_me_reconnect_attempts_total 58001
telemt_me_reconnect_success_total 15008
telemt_me_reader_eof_total 16736
telemt_me_idle_close_by_peer_total 16736
telemt_me_route_drop_no_conn_total 42900
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97147
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 14
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 16461
telemt_me_refill_failed_total 1342
telemt_me_writer_restored_same_endpoint_total 14993
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1453
telemt_user_connections_total{user="hello"} 113647
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 1232978404 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 34667917819 (32.29 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 61696.4 (17h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145059
telemt_connections_bad_total 1668
telemt_handshake_timeouts_total 2331
telemt_upstream_connect_attempt_total 16970
telemt_upstream_connect_success_total 16968
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 16970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 361
telemt_me_reconnect_attempts_total 14978
telemt_me_reconnect_success_total 13826
telemt_me_reader_eof_total 14778
telemt_me_idle_close_by_peer_total 14778
telemt_me_route_drop_no_conn_total 55213
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135632
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13997
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 13806
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 135596
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 2626283012 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 62237995864 (57.96 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 61672.0 (17h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208187
telemt_connections_bad_total 13285
telemt_handshake_timeouts_total 1426
telemt_upstream_connect_attempt_total 29026
telemt_upstream_connect_success_total 19273
telemt_upstream_connect_fail_total 9753
telemt_upstream_connect_attempts_per_request{bucket="1"} 29026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9168
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9753
telemt_me_keepalive_timeout_total 3199
telemt_me_reconnect_attempts_total 48921
telemt_me_reconnect_success_total 13305
telemt_me_reader_eof_total 14879
telemt_me_idle_close_by_peer_total 14872
telemt_me_route_drop_no_conn_total 74418
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172009
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 14618
telemt_me_refill_failed_total 1109
telemt_me_writer_restored_same_endpoint_total 13295
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1313
telemt_user_connections_total{user="hello"} 174762
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 3012737538 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 72046835941 (67.10 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 11843.7 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10766
telemt_connections_bad_total 2180
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 3725
telemt_upstream_connect_success_total 3688
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 3724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 3062
telemt_me_reconnect_success_total 3055
telemt_me_reader_eof_total 3246
telemt_me_idle_close_by_peer_total 3246
telemt_me_route_drop_no_conn_total 3286
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8203
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3071
telemt_me_writer_restored_same_endpoint_total 3039
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 8203
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 33317916 (31.77 MB)
telemt_user_octets_to_client{user="hello"} 2762145048 (2.57 GB)
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 61628.5 (17h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347701
telemt_connections_bad_total 6494
telemt_handshake_timeouts_total 2589
telemt_upstream_connect_attempt_total 13017
telemt_upstream_connect_success_total 12947
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1330
telemt_me_reconnect_attempts_total 13479
telemt_me_reconnect_success_total 9862
telemt_me_reader_eof_total 10580
telemt_me_idle_close_by_peer_total 10578
telemt_me_route_drop_no_conn_total 155503
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340298
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 300
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10096
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 9855
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 328599
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 5595104788 (5.21 GB)
telemt_user_octets_to_client{user="hello"} 176639761860 (164.51 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 26
```