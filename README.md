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

# Server Metrics 2026-03-12 18:15:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 38550.5 (10h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198063
telemt_connections_bad_total 2415
telemt_handshake_timeouts_total 4947
telemt_upstream_connect_attempt_total 9742
telemt_upstream_connect_success_total 9699
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 9742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1386
telemt_me_reconnect_attempts_total 11179
telemt_me_reconnect_success_total 7722
telemt_me_reader_eof_total 8184
telemt_me_idle_close_by_peer_total 8183
telemt_me_route_drop_no_conn_total 59135
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167297
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 633
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 395
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 7921
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 7706
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 167256
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 2969514532 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 70801716956 (65.94 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 38443.9 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85469
telemt_connections_bad_total 472
telemt_handshake_timeouts_total 671
telemt_upstream_connect_attempt_total 16767
telemt_upstream_connect_success_total 16517
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 16766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 256
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 324
telemt_me_reconnect_attempts_total 40229
telemt_me_reconnect_success_total 9054
telemt_me_reader_eof_total 10200
telemt_me_idle_close_by_peer_total 10200
telemt_me_route_drop_no_conn_total 35222
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75765
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 10
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 10100
telemt_me_refill_failed_total 973
telemt_me_writer_restored_same_endpoint_total 9039
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1046
telemt_user_connections_total{user="hello"} 81263
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 880013387 (839.25 MB)
telemt_user_octets_to_client{user="hello"} 22558146312 (21.01 GB)
telemt_user_msgs_from_client{user="hello"} 86423
telemt_user_msgs_to_client{user="hello"} 601629
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 38407.1 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112114
telemt_connections_bad_total 1513
telemt_handshake_timeouts_total 2105
telemt_upstream_connect_attempt_total 10705
telemt_upstream_connect_success_total 10705
telemt_upstream_connect_attempts_per_request{bucket="1"} 10705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5517
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 236
telemt_me_reconnect_attempts_total 8782
telemt_me_reconnect_success_total 8707
telemt_me_reader_eof_total 9205
telemt_me_idle_close_by_peer_total 9205
telemt_me_route_drop_no_conn_total 42078
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103912
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 8792
telemt_me_writer_restored_same_endpoint_total 8687
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 103885
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 2404181852 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 53093257620 (49.45 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 38382.8 (10h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153096
telemt_connections_bad_total 13099
telemt_handshake_timeouts_total 1161
telemt_upstream_connect_attempt_total 8775
telemt_upstream_connect_success_total 8504
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 8774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 376
telemt_me_reconnect_attempts_total 37169
telemt_me_reconnect_success_total 6548
telemt_me_reader_eof_total 7646
telemt_me_idle_close_by_peer_total 7646
telemt_me_route_drop_no_conn_total 56068
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131205
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 442
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 168
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 7575
telemt_me_refill_failed_total 955
telemt_me_writer_restored_same_endpoint_total 6540
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 1027
telemt_user_connections_total{user="hello"} 131087
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 2325225432 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 53923451712 (50.22 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 38352.3 (10h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97868
telemt_connections_bad_total 9884
telemt_handshake_timeouts_total 1322
telemt_upstream_connect_attempt_total 52317
telemt_upstream_connect_success_total 51855
telemt_upstream_connect_fail_total 461
telemt_upstream_connect_attempts_per_request{bucket="1"} 52316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 461
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 53403
telemt_me_reconnect_success_total 3749
telemt_me_reader_eof_total 5298
telemt_me_idle_close_by_peer_total 5298
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 14003
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36131
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 5326
telemt_me_refill_failed_total 1554
telemt_me_writer_restored_same_endpoint_total 3732
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1577
telemt_user_connections_total{user="hello"} 82286
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 734993450 (700.94 MB)
telemt_user_octets_to_client{user="hello"} 24126377437 (22.47 GB)
telemt_user_msgs_from_client{user="hello"} 705163
telemt_user_msgs_to_client{user="hello"} 2692568
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 38339.6 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244970
telemt_connections_bad_total 1273
telemt_handshake_timeouts_total 2067
telemt_upstream_connect_attempt_total 8177
telemt_upstream_connect_success_total 8138
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 465
telemt_me_reconnect_attempts_total 9790
telemt_me_reconnect_success_total 6187
telemt_me_reader_eof_total 6591
telemt_me_idle_close_by_peer_total 6590
telemt_me_route_drop_no_conn_total 112572
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243822
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6378
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6180
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 233749
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 4117505776 (3.83 GB)
telemt_user_octets_to_client{user="hello"} 107695156064 (100.30 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 47
```