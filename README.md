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

# Server Metrics 2026-03-12 17:24:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 35476.0 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185275
telemt_connections_bad_total 2413
telemt_handshake_timeouts_total 4918
telemt_upstream_connect_attempt_total 9039
telemt_upstream_connect_success_total 9005
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 9039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 368
telemt_me_reconnect_attempts_total 9332
telemt_me_reconnect_success_total 7169
telemt_me_reader_eof_total 7571
telemt_me_idle_close_by_peer_total 7570
telemt_me_route_drop_no_conn_total 53842
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157262
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 628
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 393
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7311
telemt_me_refill_failed_total 66
telemt_me_writer_restored_same_endpoint_total 7153
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 157224
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 2850210492 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 65338135304 (60.85 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 35368.9 (9h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77830
telemt_connections_bad_total 467
telemt_handshake_timeouts_total 647
telemt_upstream_connect_attempt_total 10949
telemt_upstream_connect_success_total 10710
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 10949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 302
telemt_me_reconnect_attempts_total 36074
telemt_me_reconnect_success_total 8906
telemt_me_reader_eof_total 9924
telemt_me_idle_close_by_peer_total 9924
telemt_me_route_drop_no_conn_total 34253
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73932
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 9
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
telemt_me_writer_removed_unexpected_total 9823
telemt_me_refill_failed_total 848
telemt_me_writer_restored_same_endpoint_total 8891
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 917
telemt_user_connections_total{user="hello"} 73916
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 819067040 (781.12 MB)
telemt_user_octets_to_client{user="hello"} 20319092680 (18.92 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 35332.5 (9h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104964
telemt_connections_bad_total 1506
telemt_handshake_timeouts_total 2070
telemt_upstream_connect_attempt_total 9765
telemt_upstream_connect_success_total 9765
telemt_upstream_connect_attempts_per_request{bucket="1"} 9765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 207
telemt_me_reconnect_attempts_total 7975
telemt_me_reconnect_success_total 7905
telemt_me_reader_eof_total 8379
telemt_me_idle_close_by_peer_total 8379
telemt_me_route_drop_no_conn_total 39183
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97120
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
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 7978
telemt_me_writer_restored_same_endpoint_total 7885
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 97093
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 2312660152 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 51535662084 (48.00 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 35308.3 (9h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143850
telemt_connections_bad_total 13068
telemt_handshake_timeouts_total 1082
telemt_upstream_connect_attempt_total 7654
telemt_upstream_connect_success_total 7411
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 7654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_keepalive_timeout_total 358
telemt_me_reconnect_attempts_total 33681
telemt_me_reconnect_success_total 5588
telemt_me_reader_eof_total 6604
telemt_me_idle_close_by_peer_total 6604
telemt_me_route_drop_no_conn_total 51559
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122473
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 413
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 118
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 6532
telemt_me_refill_failed_total 876
telemt_me_writer_restored_same_endpoint_total 5580
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 944
telemt_user_connections_total{user="hello"} 122355
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 2203191228 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 51713539880 (48.16 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 35277.6 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87319
telemt_connections_bad_total 9273
telemt_handshake_timeouts_total 1156
telemt_upstream_connect_attempt_total 45668
telemt_upstream_connect_success_total 45231
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 45668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6646
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 48405
telemt_me_reconnect_success_total 3714
telemt_me_reader_eof_total 5108
telemt_me_idle_close_by_peer_total 5108
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 13231
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34960
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 12
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
telemt_me_writer_removed_unexpected_total 5136
telemt_me_refill_failed_total 1399
telemt_me_writer_restored_same_endpoint_total 3697
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1422
telemt_user_connections_total{user="hello"} 74660
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 695538008 (663.32 MB)
telemt_user_octets_to_client{user="hello"} 22529850438 (20.98 GB)
telemt_user_msgs_from_client{user="hello"} 638030
telemt_user_msgs_to_client{user="hello"} 2445761
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 35265.7 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224928
telemt_connections_bad_total 1024
telemt_handshake_timeouts_total 1785
telemt_upstream_connect_attempt_total 7601
telemt_upstream_connect_success_total 7563
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 7601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 8929
telemt_me_reconnect_success_total 5746
telemt_me_reader_eof_total 6111
telemt_me_idle_close_by_peer_total 6110
telemt_me_route_drop_no_conn_total 102719
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224923
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
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5920
telemt_me_refill_failed_total 98
telemt_me_writer_restored_same_endpoint_total 5739
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 214860
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 3865997784 (3.60 GB)
telemt_user_octets_to_client{user="hello"} 98202711732 (91.46 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 61
```