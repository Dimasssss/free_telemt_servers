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

# Server Metrics 2026-03-13 00:28:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 60918.7 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256774
telemt_connections_bad_total 2753
telemt_handshake_timeouts_total 5284
telemt_upstream_connect_attempt_total 15321
telemt_upstream_connect_success_total 15254
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 15321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1496
telemt_me_reconnect_attempts_total 15654
telemt_me_reconnect_success_total 12181
telemt_me_reader_eof_total 12987
telemt_me_idle_close_by_peer_total 12986
telemt_me_route_drop_no_conn_total 79905
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212652
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 717
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 267
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12426
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 12165
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 212420
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 3895964656 (3.63 GB)
telemt_user_octets_to_client{user="hello"} 108146414408 (100.72 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 60811.6 (16h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118627
telemt_connections_bad_total 710
telemt_handshake_timeouts_total 963
telemt_upstream_connect_attempt_total 34549
telemt_upstream_connect_success_total 34146
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 34549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 500
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_keepalive_timeout_total 429
telemt_me_reconnect_attempts_total 56460
telemt_me_reconnect_success_total 14588
telemt_me_reader_eof_total 16275
telemt_me_idle_close_by_peer_total 16275
telemt_me_route_drop_no_conn_total 42608
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96044
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 14
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 16000
telemt_me_refill_failed_total 1307
telemt_me_writer_restored_same_endpoint_total 14573
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1412
telemt_user_connections_total{user="hello"} 112544
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 1228922896 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 34571762127 (32.20 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 60775.0 (16h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144124
telemt_connections_bad_total 1665
telemt_handshake_timeouts_total 2322
telemt_upstream_connect_attempt_total 16708
telemt_upstream_connect_success_total 16706
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 16708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8871
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 356
telemt_me_reconnect_attempts_total 14759
telemt_me_reconnect_success_total 13607
telemt_me_reader_eof_total 14542
telemt_me_idle_close_by_peer_total 14542
telemt_me_route_drop_no_conn_total 54637
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134748
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
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13776
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 13587
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 134712
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 2623706792 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 62221033576 (57.95 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 60750.8 (16h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207198
telemt_connections_bad_total 13283
telemt_handshake_timeouts_total 1394
telemt_upstream_connect_attempt_total 28719
telemt_upstream_connect_success_total 18980
telemt_upstream_connect_fail_total 9739
telemt_upstream_connect_attempts_per_request{bucket="1"} 28719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8984
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9739
telemt_me_keepalive_timeout_total 3194
telemt_me_reconnect_attempts_total 47359
telemt_me_reconnect_success_total 13056
telemt_me_reader_eof_total 14587
telemt_me_idle_close_by_peer_total 14580
telemt_me_route_drop_no_conn_total 73901
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171066
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 12
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
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 14326
telemt_me_refill_failed_total 1068
telemt_me_writer_restored_same_endpoint_total 13046
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1270
telemt_user_connections_total{user="hello"} 173820
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 3006749834 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 71608726853 (66.69 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 10922.5 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9847
telemt_connections_bad_total 2016
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 3437
telemt_upstream_connect_success_total 3402
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 3437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1879
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 2818
telemt_me_reconnect_success_total 2812
telemt_me_reader_eof_total 2986
telemt_me_idle_close_by_peer_total 2986
telemt_me_route_drop_no_conn_total 3007
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7475
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2825
telemt_me_writer_restored_same_endpoint_total 2796
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 7475
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 28678632 (27.35 MB)
telemt_user_octets_to_client{user="hello"} 2722266848 (2.54 GB)
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 60707.3 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344948
telemt_connections_bad_total 6484
telemt_handshake_timeouts_total 2561
telemt_upstream_connect_attempt_total 12830
telemt_upstream_connect_success_total 12760
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 12830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1330
telemt_me_reconnect_attempts_total 13336
telemt_me_reconnect_success_total 9719
telemt_me_reader_eof_total 10429
telemt_me_idle_close_by_peer_total 10427
telemt_me_route_drop_no_conn_total 154167
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337679
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 298
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 9951
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 9712
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 325979
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 5577222560 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 175584218748 (163.53 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 29
```