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

# Server Metrics 2026-03-15 14:48:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 59624.7 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269710
telemt_connections_bad_total 2549
telemt_handshake_timeouts_total 7425
telemt_upstream_connect_attempt_total 15009
telemt_upstream_connect_success_total 14931
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 15009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15311
telemt_me_reconnect_success_total 11930
telemt_me_reader_eof_total 12721
telemt_me_idle_close_by_peer_total 12721
telemt_me_route_drop_no_conn_total 441701
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310038
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1714
telemt_desync_full_logged_total 685
telemt_desync_suppressed_total 1029
telemt_desync_frames_bucket_total{bucket="1_2"} 307
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 736
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12157
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11899
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 249145
telemt_user_connections_current{user="hello"} 415
telemt_user_octets_from_client{user="hello"} 5448572280 (5.07 GB)
telemt_user_octets_to_client{user="hello"} 214320296304 (199.60 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 59631.1 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100061
telemt_connections_bad_total 2793
telemt_handshake_timeouts_total 9618
telemt_upstream_connect_attempt_total 16514
telemt_upstream_connect_success_total 16514
telemt_upstream_connect_attempts_per_request{bucket="1"} 16514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 15828
telemt_me_reconnect_success_total 13473
telemt_me_reader_eof_total 14413
telemt_me_idle_close_by_peer_total 14413
telemt_me_route_drop_no_conn_total 42282
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84596
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13703
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 13457
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 84587
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 1653128116 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 40215142204 (37.45 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 59623.4 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109260
telemt_connections_bad_total 1652
telemt_handshake_timeouts_total 2797
telemt_upstream_connect_attempt_total 17617
telemt_upstream_connect_success_total 17608
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 17616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9968
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 21906
telemt_me_reconnect_success_total 14563
telemt_me_reader_eof_total 15653
telemt_me_idle_close_by_peer_total 15653
telemt_me_route_drop_no_conn_total 41080
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94191
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 14926
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 14555
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 363
telemt_user_connections_total{user="hello"} 94092
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 10200191288 (9.50 GB)
telemt_user_octets_to_client{user="hello"} 54777710676 (51.02 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 59623.3 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144477
telemt_connections_bad_total 797
telemt_handshake_timeouts_total 923
telemt_upstream_connect_attempt_total 14377
telemt_upstream_connect_success_total 14373
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 14377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 11440
telemt_me_reconnect_success_total 11370
telemt_me_reader_eof_total 12103
telemt_me_idle_close_by_peer_total 12103
telemt_me_route_drop_no_conn_total 56146
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132190
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 463
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 316
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 211
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 11502
telemt_me_writer_restored_same_endpoint_total 11359
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 132107
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 2471257676 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 64540784168 (60.11 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 34694.7 (9h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83646
telemt_connections_bad_total 21522
telemt_handshake_timeouts_total 1431
telemt_upstream_connect_attempt_total 10928
telemt_upstream_connect_success_total 10861
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 10928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 103364
telemt_me_reconnect_success_total 8934
telemt_me_reader_eof_total 9339
telemt_me_idle_close_by_peer_total 9339
telemt_me_route_drop_no_conn_total 28597
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58780
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 155
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 8954
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 8830
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 58917
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 857195465 (817.49 MB)
telemt_user_octets_to_client{user="hello"} 23664732655 (22.04 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 59622.9 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361887
telemt_connections_bad_total 48763
telemt_handshake_timeouts_total 3012
telemt_upstream_connect_attempt_total 12793
telemt_upstream_connect_success_total 12716
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 12793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 10984
telemt_me_reconnect_success_total 9697
telemt_me_reader_eof_total 10336
telemt_me_idle_close_by_peer_total 10336
telemt_me_route_drop_no_conn_total 169031
telemt_me_route_drop_channel_closed_total 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299381
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 9829
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 9670
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 297178
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 7487399016 (6.97 GB)
telemt_user_octets_to_client{user="hello"} 151628850960 (141.22 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 63
```