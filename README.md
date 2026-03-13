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

# Server Metrics 2026-03-13 05:30:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 79031.2 (21h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300319
telemt_connections_bad_total 3068
telemt_handshake_timeouts_total 6159
telemt_upstream_connect_attempt_total 19900
telemt_upstream_connect_success_total 19807
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 19900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1560
telemt_me_reconnect_attempts_total 19344
telemt_me_reconnect_success_total 15847
telemt_me_reader_eof_total 16945
telemt_me_idle_close_by_peer_total 16944
telemt_me_route_drop_no_conn_total 93803
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252909
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 861
telemt_desync_full_logged_total 321
telemt_desync_suppressed_total 540
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 313
telemt_desync_frames_bucket_total{bucket="gt_10"} 377
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16127
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15831
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 252846
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 4318334032 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 123375943924 (114.90 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 78923.9 (21h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137165
telemt_connections_bad_total 759
telemt_handshake_timeouts_total 1035
telemt_upstream_connect_attempt_total 41879
telemt_upstream_connect_success_total 41349
telemt_upstream_connect_fail_total 530
telemt_upstream_connect_attempts_per_request{bucket="1"} 41879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 508
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 530
telemt_me_keepalive_timeout_total 587
telemt_me_reconnect_attempts_total 67471
telemt_me_reconnect_success_total 20907
telemt_me_reader_eof_total 23011
telemt_me_idle_close_by_peer_total 23011
telemt_me_route_drop_no_conn_total 51037
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113843
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
telemt_me_writer_removed_unexpected_total 22526
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 20892
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1619
telemt_user_connections_total{user="hello"} 130343
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 1355447720 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 39553087363 (36.84 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 78887.6 (21h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165975
telemt_connections_bad_total 1860
telemt_handshake_timeouts_total 2680
telemt_upstream_connect_attempt_total 21765
telemt_upstream_connect_success_total 21763
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 21765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11727
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 463
telemt_me_reconnect_attempts_total 18949
telemt_me_reconnect_success_total 17782
telemt_me_reader_eof_total 19052
telemt_me_idle_close_by_peer_total 19052
telemt_me_route_drop_no_conn_total 64444
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155246
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
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 17976
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17762
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 155173
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 2912655372 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 71138623600 (66.25 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 78863.4 (21h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239724
telemt_connections_bad_total 13565
telemt_handshake_timeouts_total 1796
telemt_upstream_connect_attempt_total 33953
telemt_upstream_connect_success_total 24054
telemt_upstream_connect_fail_total 9899
telemt_upstream_connect_attempts_per_request{bucket="1"} 33953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11762
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9899
telemt_me_keepalive_timeout_total 3317
telemt_me_reconnect_attempts_total 68785
telemt_me_reconnect_success_total 17255
telemt_me_reader_eof_total 19388
telemt_me_idle_close_by_peer_total 19381
telemt_me_route_drop_no_conn_total 87433
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200959
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 567
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 19089
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 17245
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1834
telemt_user_connections_total{user="hello"} 203702
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 3291924066 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 81232782417 (75.65 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 29034.9 (8h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30774
telemt_connections_bad_total 5453
telemt_handshake_timeouts_total 132
telemt_upstream_connect_attempt_total 9728
telemt_upstream_connect_success_total 9635
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 9728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 234
telemt_me_reconnect_attempts_total 9118
telemt_me_reconnect_success_total 8160
telemt_me_reader_eof_total 8725
telemt_me_idle_close_by_peer_total 8725
telemt_me_route_drop_no_conn_total 8598
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24356
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 8266
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 8142
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 24356
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 197837776 (188.67 MB)
telemt_user_octets_to_client{user="hello"} 9400228076 (8.75 GB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 78819.8 (21h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404522
telemt_connections_bad_total 7747
telemt_handshake_timeouts_total 3023
telemt_upstream_connect_attempt_total 16791
telemt_upstream_connect_success_total 16697
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 16791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8888
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 1450
telemt_me_reconnect_attempts_total 16407
telemt_me_reconnect_success_total 12776
telemt_me_reader_eof_total 13719
telemt_me_idle_close_by_peer_total 13716
telemt_me_route_drop_no_conn_total 179727
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392924
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 13051
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12769
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 381174
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 6302619484 (5.87 GB)
telemt_user_octets_to_client{user="hello"} 222979639376 (207.67 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 55
```