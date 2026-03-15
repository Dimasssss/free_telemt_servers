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

# Server Metrics 2026-03-15 08:05:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 35443.8 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120966
telemt_connections_bad_total 971
telemt_handshake_timeouts_total 2797
telemt_upstream_connect_attempt_total 8575
telemt_upstream_connect_success_total 8523
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 8574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4685
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 6776
telemt_me_reconnect_success_total 6750
telemt_me_reader_eof_total 7230
telemt_me_idle_close_by_peer_total 7230
telemt_me_route_drop_no_conn_total 210426
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142827
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 916
telemt_desync_full_logged_total 393
telemt_desync_suppressed_total 523
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 379
telemt_desync_frames_bucket_total{bucket="gt_10"} 384
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6812
telemt_me_writer_restored_same_endpoint_total 6719
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 112621
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 1604069020 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 100346233952 (93.45 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 35451.0 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37515
telemt_connections_bad_total 253
telemt_handshake_timeouts_total 1316
telemt_upstream_connect_attempt_total 9461
telemt_upstream_connect_success_total 9461
telemt_upstream_connect_attempts_per_request{bucket="1"} 9461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7706
telemt_me_reconnect_success_total 7671
telemt_me_reader_eof_total 8238
telemt_me_idle_close_by_peer_total 8238
telemt_me_route_drop_no_conn_total 19769
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34574
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7748
telemt_me_writer_restored_same_endpoint_total 7655
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 34577
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 829881184 (791.44 MB)
telemt_user_octets_to_client{user="hello"} 12956368700 (12.07 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 35443.5 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47681
telemt_connections_bad_total 479
telemt_handshake_timeouts_total 1891
telemt_upstream_connect_attempt_total 9405
telemt_upstream_connect_success_total 9404
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7653
telemt_me_reconnect_success_total 7618
telemt_me_reader_eof_total 8231
telemt_me_idle_close_by_peer_total 8231
telemt_me_route_drop_no_conn_total 16256
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43215
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7688
telemt_me_writer_restored_same_endpoint_total 7614
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 43153
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 8896771072 (8.29 GB)
telemt_user_octets_to_client{user="hello"} 24266882560 (22.60 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 35443.1 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56200
telemt_connections_bad_total 153
telemt_handshake_timeouts_total 386
telemt_upstream_connect_attempt_total 8389
telemt_upstream_connect_success_total 8388
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6640
telemt_me_reconnect_success_total 6613
telemt_me_reader_eof_total 7065
telemt_me_idle_close_by_peer_total 7065
telemt_me_route_drop_no_conn_total 24515
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50861
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 98
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6683
telemt_me_writer_restored_same_endpoint_total 6602
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 50795
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 964037020 (919.38 MB)
telemt_user_octets_to_client{user="hello"} 30857649052 (28.74 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 10514.5 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16167
telemt_connections_bad_total 2017
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 3876
telemt_upstream_connect_success_total 3838
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 3876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 97533
telemt_me_reconnect_success_total 3133
telemt_me_reader_eof_total 3209
telemt_me_idle_close_by_peer_total 3209
telemt_me_route_drop_no_conn_total 4725
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13493
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3082
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 3029
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 13633
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 98577725 (94.01 MB)
telemt_user_octets_to_client{user="hello"} 9190556383 (8.56 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 35442.6 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151314
telemt_connections_bad_total 19910
telemt_handshake_timeouts_total 739
telemt_upstream_connect_attempt_total 7695
telemt_upstream_connect_success_total 7649
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 7695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_reconnect_attempts_total 5895
telemt_me_reconnect_success_total 5865
telemt_me_reader_eof_total 6248
telemt_me_idle_close_by_peer_total 6248
telemt_me_route_drop_no_conn_total 72172
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126661
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5897
telemt_me_writer_restored_same_endpoint_total 5838
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 125199
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 3462062848 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 67599469812 (62.96 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 63
```