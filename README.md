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

# Server Metrics 2026-03-13 09:15:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 92551.2 (25h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362067
telemt_connections_bad_total 3186
telemt_handshake_timeouts_total 7820
telemt_upstream_connect_attempt_total 23379
telemt_upstream_connect_success_total 23270
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 23379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1714
telemt_me_reconnect_attempts_total 22147
telemt_me_reconnect_success_total 18635
telemt_me_reader_eof_total 19911
telemt_me_idle_close_by_peer_total 19910
telemt_me_route_drop_no_conn_total 113921
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309944
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
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 18941
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 18619
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 309636
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 5047130912 (4.70 GB)
telemt_user_octets_to_client{user="hello"} 139141912244 (129.59 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 92443.9 (25h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165420
telemt_connections_bad_total 1521
telemt_handshake_timeouts_total 1249
telemt_upstream_connect_attempt_total 46156
telemt_upstream_connect_success_total 45527
telemt_upstream_connect_fail_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 46156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 514
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 629
telemt_me_keepalive_timeout_total 705
telemt_me_reconnect_attempts_total 79796
telemt_me_reconnect_success_total 24421
telemt_me_reader_eof_total 26887
telemt_me_idle_close_by_peer_total 26887
telemt_me_route_drop_no_conn_total 63437
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139196
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
telemt_me_writer_removed_unexpected_total 26353
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 24406
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1932
telemt_user_connections_total{user="hello"} 155685
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 1623737156 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 50076197487 (46.64 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 92407.7 (25h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202019
telemt_connections_bad_total 2004
telemt_handshake_timeouts_total 4132
telemt_upstream_connect_attempt_total 25002
telemt_upstream_connect_success_total 24999
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 25002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13497
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 638
telemt_me_reconnect_attempts_total 21533
telemt_me_reconnect_success_total 20346
telemt_me_reader_eof_total 21822
telemt_me_idle_close_by_peer_total 21822
telemt_me_route_drop_no_conn_total 76391
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188438
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
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 20569
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20326
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 188363
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 7052686432 (6.57 GB)
telemt_user_octets_to_client{user="hello"} 78237741956 (72.86 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 92383.1 (25h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287836
telemt_connections_bad_total 13663
telemt_handshake_timeouts_total 2139
telemt_upstream_connect_attempt_total 38087
telemt_upstream_connect_success_total 28093
telemt_upstream_connect_fail_total 9994
telemt_upstream_connect_attempts_per_request{bucket="1"} 38087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13873
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9994
telemt_me_keepalive_timeout_total 3422
telemt_me_reconnect_attempts_total 75912
telemt_me_reconnect_success_total 20622
telemt_me_reader_eof_total 22988
telemt_me_idle_close_by_peer_total 22981
telemt_me_route_drop_no_conn_total 103835
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245637
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 910
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 643
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 22610
telemt_me_refill_failed_total 1723
telemt_me_writer_restored_same_endpoint_total 20612
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1988
telemt_user_connections_total{user="hello"} 248362
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 5503059870 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 94205993509 (87.74 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 42554.7 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55077
telemt_connections_bad_total 8588
telemt_handshake_timeouts_total 466
telemt_upstream_connect_attempt_total 14811
telemt_upstream_connect_success_total 14665
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 14811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 355
telemt_me_reconnect_attempts_total 14740
telemt_me_reconnect_success_total 12515
telemt_me_reader_eof_total 13339
telemt_me_idle_close_by_peer_total 13339
telemt_me_route_drop_no_conn_total 16690
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44519
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 74
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 12696
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 12497
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 44514
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 328728804 (313.50 MB)
telemt_user_octets_to_client{user="hello"} 12113626832 (11.28 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 92339.6 (25h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495913
telemt_connections_bad_total 13583
telemt_handshake_timeouts_total 5114
telemt_upstream_connect_attempt_total 19526
telemt_upstream_connect_success_total 19422
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 19526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 1539
telemt_me_reconnect_attempts_total 18479
telemt_me_reconnect_success_total 14834
telemt_me_reader_eof_total 15926
telemt_me_idle_close_by_peer_total 15923
telemt_me_route_drop_no_conn_total 259441
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 486652
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 398
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 15139
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14827
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 305
telemt_user_connections_total{user="hello"} 459742
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 8396011444 (7.82 GB)
telemt_user_octets_to_client{user="hello"} 259645337952 (241.81 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 68
```