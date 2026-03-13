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

# Server Metrics 2026-03-13 02:57:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 69820.6 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274584
telemt_connections_bad_total 2910
telemt_handshake_timeouts_total 5655
telemt_upstream_connect_attempt_total 17695
telemt_upstream_connect_success_total 17616
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 17695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1524
telemt_me_reconnect_attempts_total 17583
telemt_me_reconnect_success_total 14098
telemt_me_reader_eof_total 15065
telemt_me_idle_close_by_peer_total 15064
telemt_me_route_drop_no_conn_total 85467
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228898
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 768
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 484
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 349
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 14362
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 14082
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 228666
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 4036487412 (3.76 GB)
telemt_user_octets_to_client{user="hello"} 112571227960 (104.84 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 69713.5 (19h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126829
telemt_connections_bad_total 742
telemt_handshake_timeouts_total 982
telemt_upstream_connect_attempt_total 38448
telemt_upstream_connect_success_total 37981
telemt_upstream_connect_fail_total 467
telemt_upstream_connect_attempts_per_request{bucket="1"} 38448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 503
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 467
telemt_me_keepalive_timeout_total 497
telemt_me_reconnect_attempts_total 63224
telemt_me_reconnect_success_total 17981
telemt_me_reader_eof_total 19886
telemt_me_idle_close_by_peer_total 19886
telemt_me_route_drop_no_conn_total 45661
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103924
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 15
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
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 19531
telemt_me_refill_failed_total 1412
telemt_me_writer_restored_same_endpoint_total 17966
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1550
telemt_user_connections_total{user="hello"} 120424
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 1266717920 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 35682931719 (33.23 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 69677.0 (19h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152820
telemt_connections_bad_total 1822
telemt_handshake_timeouts_total 2428
telemt_upstream_connect_attempt_total 19361
telemt_upstream_connect_success_total 19359
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 19361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10392
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 385
telemt_me_reconnect_attempts_total 16978
telemt_me_reconnect_success_total 15818
telemt_me_reader_eof_total 16918
telemt_me_idle_close_by_peer_total 16918
telemt_me_route_drop_no_conn_total 58590
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142913
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
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 15991
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 15798
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 142841
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 2728874388 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 68486691544 (63.78 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 69652.8 (19h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219139
telemt_connections_bad_total 13457
telemt_handshake_timeouts_total 1436
telemt_upstream_connect_attempt_total 31708
telemt_upstream_connect_success_total 21885
telemt_upstream_connect_fail_total 9823
telemt_upstream_connect_attempts_per_request{bucket="1"} 31708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10685
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9823
telemt_me_keepalive_timeout_total 3280
telemt_me_reconnect_attempts_total 57703
telemt_me_reconnect_success_total 15522
telemt_me_reader_eof_total 17342
telemt_me_idle_close_by_peer_total 17335
telemt_me_route_drop_no_conn_total 79481
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182308
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 14
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
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 17054
telemt_me_refill_failed_total 1314
telemt_me_writer_restored_same_endpoint_total 15512
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1532
telemt_user_connections_total{user="hello"} 185059
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 3109017194 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 75872014669 (70.66 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 19824.3 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18715
telemt_connections_bad_total 3720
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 6043
telemt_upstream_connect_success_total 5988
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 6043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 5017
telemt_me_reconnect_success_total 5000
telemt_me_reader_eof_total 5358
telemt_me_idle_close_by_peer_total 5358
telemt_me_route_drop_no_conn_total 5395
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14442
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5040
telemt_me_writer_restored_same_endpoint_total 4984
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 14442
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 94685688 (90.30 MB)
telemt_user_octets_to_client{user="hello"} 6834014952 (6.36 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 69609.1 (19h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369297
telemt_connections_bad_total 6625
telemt_handshake_timeouts_total 2853
telemt_upstream_connect_attempt_total 14858
telemt_upstream_connect_success_total 14774
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 14858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 1356
telemt_me_reconnect_attempts_total 14916
telemt_me_reconnect_success_total 11295
telemt_me_reader_eof_total 12129
telemt_me_idle_close_by_peer_total 12126
telemt_me_route_drop_no_conn_total 165427
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361076
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 11547
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 11288
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 349322
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 5901268348 (5.50 GB)
telemt_user_octets_to_client{user="hello"} 212055075128 (197.49 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 34
```