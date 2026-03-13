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

# Server Metrics 2026-03-13 05:20:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 78416.6 (21h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298245
telemt_connections_bad_total 3066
telemt_handshake_timeouts_total 6129
telemt_upstream_connect_attempt_total 19778
telemt_upstream_connect_success_total 19685
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 19778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10821
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1560
telemt_me_reconnect_attempts_total 19222
telemt_me_reconnect_success_total 15725
telemt_me_reader_eof_total 16811
telemt_me_idle_close_by_peer_total 16810
telemt_me_route_drop_no_conn_total 92838
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250924
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 854
telemt_desync_full_logged_total 318
telemt_desync_suppressed_total 536
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 312
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16003
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15709
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 250861
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 4295086216 (4.00 GB)
telemt_user_octets_to_client{user="hello"} 122458111880 (114.05 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 78310.3 (21h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136448
telemt_connections_bad_total 759
telemt_handshake_timeouts_total 1033
telemt_upstream_connect_attempt_total 41629
telemt_upstream_connect_success_total 41110
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 41629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16074
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 508
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_timeout_total 585
telemt_me_reconnect_attempts_total 67275
telemt_me_reconnect_success_total 20712
telemt_me_reader_eof_total 22816
telemt_me_idle_close_by_peer_total 22816
telemt_me_route_drop_no_conn_total 50588
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113142
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
telemt_me_writer_removed_unexpected_total 22331
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 20697
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1619
telemt_user_connections_total{user="hello"} 129642
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 1351484564 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 39338086703 (36.64 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 78273.9 (21h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164939
telemt_connections_bad_total 1859
telemt_handshake_timeouts_total 2669
telemt_upstream_connect_attempt_total 21567
telemt_upstream_connect_success_total 21565
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 21567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11617
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 460
telemt_me_reconnect_attempts_total 18794
telemt_me_reconnect_success_total 17628
telemt_me_reader_eof_total 18882
telemt_me_idle_close_by_peer_total 18882
telemt_me_route_drop_no_conn_total 63911
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154258
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
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17821
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17608
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 154185
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 2905595584 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 70952009344 (66.08 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 78249.5 (21h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238330
telemt_connections_bad_total 13565
telemt_handshake_timeouts_total 1795
telemt_upstream_connect_attempt_total 33845
telemt_upstream_connect_success_total 23953
telemt_upstream_connect_fail_total 9892
telemt_upstream_connect_attempts_per_request{bucket="1"} 33845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9892
telemt_me_keepalive_timeout_total 3315
telemt_me_reconnect_attempts_total 67351
telemt_me_reconnect_success_total 17197
telemt_me_reader_eof_total 19287
telemt_me_idle_close_by_peer_total 19280
telemt_me_route_drop_no_conn_total 86778
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199620
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 560
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 404
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 18988
telemt_me_refill_failed_total 1563
telemt_me_writer_restored_same_endpoint_total 17187
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1791
telemt_user_connections_total{user="hello"} 202363
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 3284523830 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 80892172393 (75.34 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 28421.1 (7h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29894
telemt_connections_bad_total 5344
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 9416
telemt_upstream_connect_success_total 9325
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 9416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 8851
telemt_me_reconnect_success_total 7893
telemt_me_reader_eof_total 8416
telemt_me_idle_close_by_peer_total 8416
telemt_me_route_drop_no_conn_total 8277
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23604
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7997
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 7875
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 23604
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 196056932 (186.97 MB)
telemt_user_octets_to_client{user="hello"} 9372461992 (8.73 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 78206.1 (21h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400863
telemt_connections_bad_total 7742
telemt_handshake_timeouts_total 2979
telemt_upstream_connect_attempt_total 16629
telemt_upstream_connect_success_total 16536
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8806
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1447
telemt_me_reconnect_attempts_total 16290
telemt_me_reconnect_success_total 12659
telemt_me_reader_eof_total 13591
telemt_me_idle_close_by_peer_total 13588
telemt_me_route_drop_no_conn_total 178658
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390178
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 331
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 12934
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12652
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 378420
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 6251337708 (5.82 GB)
telemt_user_octets_to_client{user="hello"} 222291981464 (207.03 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 52
```