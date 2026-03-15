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

# Server Metrics 2026-03-15 12:50:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 52578.3 (14h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231418
telemt_connections_bad_total 1976
telemt_handshake_timeouts_total 4821
telemt_upstream_connect_attempt_total 13298
telemt_upstream_connect_success_total 13228
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7327
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13960
telemt_me_reconnect_success_total 10587
telemt_me_reader_eof_total 11316
telemt_me_idle_close_by_peer_total 11316
telemt_me_route_drop_no_conn_total 428187
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 276849
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1571
telemt_desync_full_logged_total 627
telemt_desync_suppressed_total 944
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 629
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10800
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10556
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 215958
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 4384748316 (4.08 GB)
telemt_user_octets_to_client{user="hello"} 197652052924 (184.08 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 52584.6 (14h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83146
telemt_connections_bad_total 2706
telemt_handshake_timeouts_total 7029
telemt_upstream_connect_attempt_total 14517
telemt_upstream_connect_success_total 14517
telemt_upstream_connect_attempts_per_request{bucket="1"} 14517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 14186
telemt_me_reconnect_success_total 11847
telemt_me_reader_eof_total 12684
telemt_me_idle_close_by_peer_total 12684
telemt_me_route_drop_no_conn_total 36296
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70846
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 12049
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 11831
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 70843
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 1438849524 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 34377075760 (32.02 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 52577.3 (14h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85925
telemt_connections_bad_total 1044
telemt_handshake_timeouts_total 2652
telemt_upstream_connect_attempt_total 15320
telemt_upstream_connect_success_total 15312
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 15320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 14789
telemt_me_reconnect_success_total 12642
telemt_me_reader_eof_total 13535
telemt_me_idle_close_by_peer_total 13535
telemt_me_route_drop_no_conn_total 33209
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78505
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 12829
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 12634
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 78419
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 9619719116 (8.96 GB)
telemt_user_octets_to_client{user="hello"} 48197312144 (44.89 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 52576.7 (14h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117792
telemt_connections_bad_total 396
telemt_handshake_timeouts_total 763
telemt_upstream_connect_attempt_total 12339
telemt_upstream_connect_success_total 12338
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9755
telemt_me_reconnect_success_total 9699
telemt_me_reader_eof_total 10352
telemt_me_idle_close_by_peer_total 10352
telemt_me_route_drop_no_conn_total 46635
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107388
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 204
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9807
telemt_me_writer_restored_same_endpoint_total 9688
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 107308
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 1914375904 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 57269301756 (53.34 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 27648.2 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63606
telemt_connections_bad_total 16340
telemt_handshake_timeouts_total 875
telemt_upstream_connect_attempt_total 8811
telemt_upstream_connect_success_total 8750
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 8811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 101609
telemt_me_reconnect_success_total 7189
telemt_me_reader_eof_total 7501
telemt_me_idle_close_by_peer_total 7501
telemt_me_route_drop_no_conn_total 22292
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44936
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7184
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 7085
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 45071
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 673548117 (642.35 MB)
telemt_user_octets_to_client{user="hello"} 17648023499 (16.44 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 52576.1 (14h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305595
telemt_connections_bad_total 47767
telemt_handshake_timeouts_total 2480
telemt_upstream_connect_attempt_total 11171
telemt_upstream_connect_success_total 11102
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 11171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 8508
telemt_me_reconnect_success_total 8449
telemt_me_reader_eof_total 8992
telemt_me_idle_close_by_peer_total 8992
telemt_me_route_drop_no_conn_total 136125
telemt_me_route_drop_channel_closed_total 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246319
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 203
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 136
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8526
telemt_me_writer_restored_same_endpoint_total 8422
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 244680
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 5093019504 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 116633408064 (108.62 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 60
```