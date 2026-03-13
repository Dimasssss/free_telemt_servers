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

# Server Metrics 2026-03-13 06:57:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 84255.1 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319761
telemt_connections_bad_total 3139
telemt_handshake_timeouts_total 6739
telemt_upstream_connect_attempt_total 21209
telemt_upstream_connect_success_total 21111
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 21209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1639
telemt_me_reconnect_attempts_total 20387
telemt_me_reconnect_success_total 16884
telemt_me_reader_eof_total 18054
telemt_me_idle_close_by_peer_total 18053
telemt_me_route_drop_no_conn_total 99373
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270924
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 928
telemt_desync_full_logged_total 344
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 17174
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16868
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 270855
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 4574371608 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 128043144548 (119.25 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 84148.0 (23h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146524
telemt_connections_bad_total 1422
telemt_handshake_timeouts_total 1126
telemt_upstream_connect_attempt_total 43727
telemt_upstream_connect_success_total 43154
telemt_upstream_connect_fail_total 572
telemt_upstream_connect_attempts_per_request{bucket="1"} 43726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 509
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 572
telemt_me_keepalive_timeout_total 637
telemt_me_reconnect_attempts_total 71640
telemt_me_reconnect_success_total 22445
telemt_me_reader_eof_total 24661
telemt_me_idle_close_by_peer_total 24661
telemt_me_route_drop_no_conn_total 55218
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122142
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 17
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
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 24160
telemt_me_refill_failed_total 1535
telemt_me_writer_restored_same_endpoint_total 22430
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1715
telemt_user_connections_total{user="hello"} 138637
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 1434160136 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 45123694611 (42.02 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 84112.0 (23h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177576
telemt_connections_bad_total 1912
telemt_handshake_timeouts_total 2896
telemt_upstream_connect_attempt_total 22974
telemt_upstream_connect_success_total 22972
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12353
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 509
telemt_me_reconnect_attempts_total 19898
telemt_me_reconnect_success_total 18725
telemt_me_reader_eof_total 20073
telemt_me_idle_close_by_peer_total 20073
telemt_me_route_drop_no_conn_total 68460
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166160
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
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 18925
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18705
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 166087
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 2986943520 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 73652274812 (68.59 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 84087.4 (23h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255383
telemt_connections_bad_total 13611
telemt_handshake_timeouts_total 1949
telemt_upstream_connect_attempt_total 35582
telemt_upstream_connect_success_total 25641
telemt_upstream_connect_fail_total 9941
telemt_upstream_connect_attempts_per_request{bucket="1"} 35582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12601
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9941
telemt_me_keepalive_timeout_total 3353
telemt_me_reconnect_attempts_total 70114
telemt_me_reconnect_success_total 18575
telemt_me_reader_eof_total 20761
telemt_me_idle_close_by_peer_total 20754
telemt_me_route_drop_no_conn_total 92349
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215471
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 650
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 20427
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18565
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1852
telemt_user_connections_total{user="hello"} 218204
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 4330192974 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 84114637869 (78.34 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 34259.0 (9h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40362
telemt_connections_bad_total 7093
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 11708
telemt_upstream_connect_success_total 11592
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 11708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 281
telemt_me_reconnect_attempts_total 10837
telemt_me_reconnect_success_total 9870
telemt_me_reader_eof_total 10525
telemt_me_idle_close_by_peer_total 10525
telemt_me_route_drop_no_conn_total 11375
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32069
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 9989
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 9852
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 32069
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 239644656 (228.54 MB)
telemt_user_octets_to_client{user="hello"} 10463657932 (9.75 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 84043.9 (23h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432714
telemt_connections_bad_total 8865
telemt_handshake_timeouts_total 3274
telemt_upstream_connect_attempt_total 17919
telemt_upstream_connect_success_total 17822
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 1457
telemt_me_reconnect_attempts_total 17273
telemt_me_reconnect_success_total 13637
telemt_me_reader_eof_total 14648
telemt_me_idle_close_by_peer_total 14645
telemt_me_route_drop_no_conn_total 191248
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 417891
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 362
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 13922
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13630
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 406122
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 6572096132 (6.12 GB)
telemt_user_octets_to_client{user="hello"} 235450910672 (219.28 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 54
```