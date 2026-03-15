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

# Server Metrics 2026-03-15 15:29:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 62074.0 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282491
telemt_connections_bad_total 2775
telemt_handshake_timeouts_total 8468
telemt_upstream_connect_attempt_total 15536
telemt_upstream_connect_success_total 15454
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15748
telemt_me_reconnect_success_total 12366
telemt_me_reader_eof_total 13168
telemt_me_idle_close_by_peer_total 13168
telemt_me_route_drop_no_conn_total 446555
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321081
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1748
telemt_desync_full_logged_total 698
telemt_desync_suppressed_total 1050
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 745
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12601
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12332
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 260183
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 5669048588 (5.28 GB)
telemt_user_octets_to_client{user="hello"} 219203535472 (204.15 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 62080.7 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106831
telemt_connections_bad_total 2806
telemt_handshake_timeouts_total 10088
telemt_upstream_connect_attempt_total 17102
telemt_upstream_connect_success_total 17102
telemt_upstream_connect_attempts_per_request{bucket="1"} 17102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 16329
telemt_me_reconnect_success_total 13971
telemt_me_reader_eof_total 14932
telemt_me_idle_close_by_peer_total 14932
telemt_me_route_drop_no_conn_total 44403
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90691
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 14209
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 13955
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 90677
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 1826183848 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 45525343544 (42.40 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 62073.4 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115011
telemt_connections_bad_total 1660
telemt_handshake_timeouts_total 2888
telemt_upstream_connect_attempt_total 18306
telemt_upstream_connect_success_total 18298
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 18306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 22502
telemt_me_reconnect_success_total 15154
telemt_me_reader_eof_total 16276
telemt_me_idle_close_by_peer_total 16276
telemt_me_route_drop_no_conn_total 44228
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99650
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 15522
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 15146
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 99550
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 10340443684 (9.63 GB)
telemt_user_octets_to_client{user="hello"} 57904169208 (53.93 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 62073.0 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152350
telemt_connections_bad_total 872
telemt_handshake_timeouts_total 958
telemt_upstream_connect_attempt_total 14935
telemt_upstream_connect_success_total 14931
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 14935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 11910
telemt_me_reconnect_success_total 11839
telemt_me_reader_eof_total 12584
telemt_me_idle_close_by_peer_total 12584
telemt_me_route_drop_no_conn_total 59368
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139682
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 496
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 333
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 11976
telemt_me_writer_restored_same_endpoint_total 11828
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 139595
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 2686359756 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 66566685372 (62.00 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 37144.5 (10h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90035
telemt_connections_bad_total 22087
telemt_handshake_timeouts_total 1809
telemt_upstream_connect_attempt_total 11536
telemt_upstream_connect_success_total 11467
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 11536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 103841
telemt_me_reconnect_success_total 9407
telemt_me_reader_eof_total 9851
telemt_me_idle_close_by_peer_total 9851
telemt_me_route_drop_no_conn_total 30723
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64090
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 158
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 9438
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 9303
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 64226
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 900850197 (859.12 MB)
telemt_user_octets_to_client{user="hello"} 27333683739 (25.46 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 62072.4 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 384449
telemt_connections_bad_total 49919
telemt_handshake_timeouts_total 3305
telemt_upstream_connect_attempt_total 13314
telemt_upstream_connect_success_total 13236
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 13314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 11413
telemt_me_reconnect_success_total 10117
telemt_me_reader_eof_total 10762
telemt_me_idle_close_by_peer_total 10762
telemt_me_route_drop_no_conn_total 212349
telemt_me_route_drop_channel_closed_total 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 335783
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
telemt_me_writer_removed_unexpected_total 10258
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 10090
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 317436
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 8124486044 (7.57 GB)
telemt_user_octets_to_client{user="hello"} 167656487052 (156.14 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 72
```