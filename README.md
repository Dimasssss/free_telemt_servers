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

# Server Metrics 2026-03-12 22:15:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 52941.5 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243547
telemt_connections_bad_total 2687
telemt_handshake_timeouts_total 5197
telemt_upstream_connect_attempt_total 13281
telemt_upstream_connect_success_total 13220
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 13281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1466
telemt_me_reconnect_attempts_total 14008
telemt_me_reconnect_success_total 10540
telemt_me_reader_eof_total 11218
telemt_me_idle_close_by_peer_total 11217
telemt_me_route_drop_no_conn_total 74802
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200294
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 679
telemt_desync_full_logged_total 251
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 301
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 10769
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 10524
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 200061
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 3748418136 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 97584369404 (90.88 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 52834.6 (14h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108943
telemt_connections_bad_total 565
telemt_handshake_timeouts_total 810
telemt_upstream_connect_attempt_total 31352
telemt_upstream_connect_success_total 31006
telemt_upstream_connect_fail_total 346
telemt_upstream_connect_attempts_per_request{bucket="1"} 31352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 499
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 346
telemt_me_keepalive_timeout_total 380
telemt_me_reconnect_attempts_total 52493
telemt_me_reconnect_success_total 11844
telemt_me_reader_eof_total 13382
telemt_me_idle_close_by_peer_total 13382
telemt_me_route_drop_no_conn_total 39559
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87143
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 13
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
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 13200
telemt_me_refill_failed_total 1269
telemt_me_writer_restored_same_endpoint_total 11829
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1356
telemt_user_connections_total{user="hello"} 103644
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 1146951128 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 33098044079 (30.82 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 52798.1 (14h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135348
telemt_connections_bad_total 1581
telemt_handshake_timeouts_total 2216
telemt_upstream_connect_attempt_total 14548
telemt_upstream_connect_success_total 14547
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 316
telemt_me_reconnect_attempts_total 12986
telemt_me_reconnect_success_total 11844
telemt_me_reader_eof_total 12622
telemt_me_idle_close_by_peer_total 12622
telemt_me_route_drop_no_conn_total 50882
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126428
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
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 11992
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 11824
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 126395
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 2569357296 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 59987354436 (55.87 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 52773.9 (14h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197277
telemt_connections_bad_total 13239
telemt_handshake_timeouts_total 1370
telemt_upstream_connect_attempt_total 25749
telemt_upstream_connect_success_total 16064
telemt_upstream_connect_fail_total 9685
telemt_upstream_connect_attempts_per_request{bucket="1"} 25749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7269
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9685
telemt_me_keepalive_timeout_total 2473
telemt_me_reconnect_attempts_total 42779
telemt_me_reconnect_success_total 10534
telemt_me_reader_eof_total 11913
telemt_me_idle_close_by_peer_total 11906
telemt_me_route_drop_no_conn_total 69119
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161419
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 11709
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 10524
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1175
telemt_user_connections_total{user="hello"} 164173
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 2959727914 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 67271173329 (62.65 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2945.5 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3002
telemt_connections_bad_total 528
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 810
telemt_upstream_connect_success_total 802
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 606
telemt_me_reconnect_success_total 605
telemt_me_reader_eof_total 627
telemt_me_idle_close_by_peer_total 627
telemt_me_route_drop_no_conn_total 850
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2332
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 604
telemt_me_writer_restored_same_endpoint_total 589
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 2332
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 7073872 (6.75 MB)
telemt_user_octets_to_client{user="hello"} 1064069412 (1014.78 MB)
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 52730.3 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320099
telemt_connections_bad_total 5067
telemt_handshake_timeouts_total 2479
telemt_upstream_connect_attempt_total 11006
telemt_upstream_connect_success_total 10945
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 11006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 502
telemt_me_reconnect_attempts_total 11907
telemt_me_reconnect_success_total 8298
telemt_me_reader_eof_total 8866
telemt_me_idle_close_by_peer_total 8865
telemt_me_route_drop_no_conn_total 145272
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 314743
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8514
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 8291
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 303045
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 5373797616 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 153654499580 (143.10 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 22
```