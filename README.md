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

# Server Metrics 2026-03-13 21:11:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 135516.6 (37h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 567935
telemt_connections_bad_total 16182
telemt_handshake_timeouts_total 12718
telemt_upstream_connect_attempt_total 34393
telemt_upstream_connect_success_total 34220
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 34393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5082
telemt_me_reconnect_attempts_total 31717
telemt_me_reconnect_success_total 27061
telemt_me_reader_eof_total 28889
telemt_me_idle_close_by_peer_total 28888
telemt_me_route_drop_no_conn_total 187524
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 489122
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1556
telemt_desync_full_logged_total 528
telemt_desync_suppressed_total 1028
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 578
telemt_desync_frames_bucket_total{bucket="gt_10"} 642
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 27512
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 27045
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 489017
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 14713642182 (13.70 GB)
telemt_user_octets_to_client{user="hello"} 236554887732 (220.31 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 135409.4 (37h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288170
telemt_connections_bad_total 2135
telemt_handshake_timeouts_total 1902
telemt_upstream_connect_attempt_total 137655
telemt_upstream_connect_success_total 136660
telemt_upstream_connect_fail_total 994
telemt_upstream_connect_attempts_per_request{bucket="1"} 137654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2408
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 994
telemt_me_keepalive_timeout_total 3664
telemt_me_reconnect_attempts_total 143652
telemt_me_reconnect_success_total 26576
telemt_me_reader_eof_total 30969
telemt_me_idle_close_by_peer_total 30969
telemt_me_route_drop_no_conn_total 84295
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170256
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 35
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
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 30481
telemt_me_refill_failed_total 3653
telemt_me_writer_restored_same_endpoint_total 26559
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3905
telemt_user_connections_total{user="hello"} 273369
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 2832414111 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 82967664139 (77.27 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 135373.8 (37h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334913
telemt_connections_bad_total 2657
telemt_handshake_timeouts_total 25748
telemt_upstream_connect_attempt_total 36041
telemt_upstream_connect_success_total 36036
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 36041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2837
telemt_me_reconnect_attempts_total 30474
telemt_me_reconnect_success_total 29231
telemt_me_reader_eof_total 31354
telemt_me_idle_close_by_peer_total 31354
telemt_me_route_drop_no_conn_total 119745
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294722
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 29561
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 29211
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 294624
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 12286565256 (11.44 GB)
telemt_user_octets_to_client{user="hello"} 122956649860 (114.51 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 135348.6 (37h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440387
telemt_connections_bad_total 15256
telemt_handshake_timeouts_total 4199
telemt_upstream_connect_attempt_total 63807
telemt_upstream_connect_success_total 53473
telemt_upstream_connect_fail_total 10334
telemt_upstream_connect_attempts_per_request{bucket="1"} 63807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 300
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10334
telemt_me_keepalive_timeout_total 4768
telemt_me_reconnect_attempts_total 126113
telemt_me_reconnect_success_total 27678
telemt_me_reader_eof_total 31531
telemt_me_idle_close_by_peer_total 31524
telemt_me_route_drop_no_conn_total 153147
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 371166
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1555
telemt_desync_full_logged_total 457
telemt_desync_suppressed_total 1098
telemt_desync_frames_bucket_total{bucket="1_2"} 366
telemt_desync_frames_bucket_total{bucket="3_10"} 593
telemt_desync_frames_bucket_total{bucket="gt_10"} 596
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 31102
telemt_me_refill_failed_total 3070
telemt_me_writer_restored_same_endpoint_total 27668
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3424
telemt_user_connections_total{user="hello"} 390023
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 8804319723 (8.20 GB)
telemt_user_octets_to_client{user="hello"} 143576177164 (133.72 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 85520.2 (23h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146307
telemt_connections_bad_total 20856
telemt_handshake_timeouts_total 1524
telemt_upstream_connect_attempt_total 32115
telemt_upstream_connect_success_total 31808
telemt_upstream_connect_fail_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 32115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 307
telemt_me_keepalive_timeout_total 1287
telemt_me_reconnect_attempts_total 36055
telemt_me_reconnect_success_total 22661
telemt_me_reader_eof_total 24267
telemt_me_idle_close_by_peer_total 24267
telemt_me_route_drop_no_conn_total 45118
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114434
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 608
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 23293
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22643
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 119328
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 1379731941 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 54770610783 (51.01 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 135304.8 (37h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 823911
telemt_connections_bad_total 26187
telemt_handshake_timeouts_total 25054
telemt_upstream_connect_attempt_total 27888
telemt_upstream_connect_success_total 27741
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 27888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14736
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 3116
telemt_me_reconnect_attempts_total 25670
telemt_me_reconnect_success_total 21019
telemt_me_reader_eof_total 22545
telemt_me_idle_close_by_peer_total 22542
telemt_me_route_drop_no_conn_total 392601
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 771632
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 693
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 21445
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21012
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 426
telemt_user_connections_total{user="hello"} 744494
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 13011312428 (12.12 GB)
telemt_user_octets_to_client{user="hello"} 369796166276 (344.40 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 40
```