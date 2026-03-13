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

# Server Metrics 2026-03-13 09:00:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 91628.5 (25h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357839
telemt_connections_bad_total 3183
telemt_handshake_timeouts_total 7770
telemt_upstream_connect_attempt_total 23120
telemt_upstream_connect_success_total 23011
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 23120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12592
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1679
telemt_me_reconnect_attempts_total 21932
telemt_me_reconnect_success_total 18422
telemt_me_reader_eof_total 19664
telemt_me_idle_close_by_peer_total 19663
telemt_me_route_drop_no_conn_total 112692
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305982
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 987
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 620
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 422
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 18721
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 18406
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 305674
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 5004352668 (4.66 GB)
telemt_user_octets_to_client{user="hello"} 138247799760 (128.75 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 91521.5 (25h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162735
telemt_connections_bad_total 1511
telemt_handshake_timeouts_total 1223
telemt_upstream_connect_attempt_total 45856
telemt_upstream_connect_success_total 45234
telemt_upstream_connect_fail_total 622
telemt_upstream_connect_attempts_per_request{bucket="1"} 45856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 514
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 622
telemt_me_keepalive_timeout_total 703
telemt_me_reconnect_attempts_total 79546
telemt_me_reconnect_success_total 24174
telemt_me_reader_eof_total 26634
telemt_me_idle_close_by_peer_total 26634
telemt_me_route_drop_no_conn_total 62069
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137026
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
telemt_me_writer_removed_unexpected_total 26100
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 24159
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1926
telemt_user_connections_total{user="hello"} 153518
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 1581740440 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 49360940455 (45.97 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 91485.1 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197858
telemt_connections_bad_total 2000
telemt_handshake_timeouts_total 3846
telemt_upstream_connect_attempt_total 24802
telemt_upstream_connect_success_total 24799
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13392
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 590
telemt_me_reconnect_attempts_total 21376
telemt_me_reconnect_success_total 20191
telemt_me_reader_eof_total 21655
telemt_me_idle_close_by_peer_total 21655
telemt_me_route_drop_no_conn_total 75191
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184776
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
telemt_me_writer_removed_unexpected_total 20413
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20171
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 184703
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 6753403208 (6.29 GB)
telemt_user_octets_to_client{user="hello"} 76930315308 (71.65 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 91460.4 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284423
telemt_connections_bad_total 13662
telemt_handshake_timeouts_total 2127
telemt_upstream_connect_attempt_total 37834
telemt_upstream_connect_success_total 27847
telemt_upstream_connect_fail_total 9987
telemt_upstream_connect_attempts_per_request{bucket="1"} 37834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9987
telemt_me_keepalive_timeout_total 3398
telemt_me_reconnect_attempts_total 74336
telemt_me_reconnect_success_total 20422
telemt_me_reader_eof_total 22745
telemt_me_idle_close_by_peer_total 22738
telemt_me_route_drop_no_conn_total 102701
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242435
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 892
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 628
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 329
telemt_desync_frames_bucket_total{bucket="gt_10"} 335
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 22367
telemt_me_refill_failed_total 1680
telemt_me_writer_restored_same_endpoint_total 20412
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1945
telemt_user_connections_total{user="hello"} 245160
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 5488784390 (5.11 GB)
telemt_user_octets_to_client{user="hello"} 93351547945 (86.94 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 41632.1 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53341
telemt_connections_bad_total 8424
telemt_handshake_timeouts_total 448
telemt_upstream_connect_attempt_total 14450
telemt_upstream_connect_success_total 14306
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 14450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 345
telemt_me_reconnect_attempts_total 14424
telemt_me_reconnect_success_total 12200
telemt_me_reader_eof_total 12995
telemt_me_idle_close_by_peer_total 12995
telemt_me_route_drop_no_conn_total 16049
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43012
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
telemt_me_writer_removed_unexpected_total 12377
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 12182
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 43010
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 313763384 (299.23 MB)
telemt_user_octets_to_client{user="hello"} 11863128784 (11.05 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 91417.1 (25h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 488933
telemt_connections_bad_total 13397
telemt_handshake_timeouts_total 4758
telemt_upstream_connect_attempt_total 19312
telemt_upstream_connect_success_total 19209
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 19312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 1539
telemt_me_reconnect_attempts_total 18313
telemt_me_reconnect_success_total 14668
telemt_me_reader_eof_total 15759
telemt_me_idle_close_by_peer_total 15756
telemt_me_route_drop_no_conn_total 256168
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 480388
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 397
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 14972
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14661
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 453483
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 8337802652 (7.77 GB)
telemt_user_octets_to_client{user="hello"} 257505491656 (239.82 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 56
```