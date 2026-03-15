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

# Server Metrics 2026-03-15 13:06:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 53497.5 (14h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237331
telemt_connections_bad_total 2217
telemt_handshake_timeouts_total 5132
telemt_upstream_connect_attempt_total 13480
telemt_upstream_connect_success_total 13410
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 14098
telemt_me_reconnect_success_total 10725
telemt_me_reader_eof_total 11463
telemt_me_idle_close_by_peer_total 11463
telemt_me_route_drop_no_conn_total 430060
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281982
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1616
telemt_desync_full_logged_total 643
telemt_desync_suppressed_total 973
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 693
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10939
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10694
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 221086
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 4604083768 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 200119217624 (186.38 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 53503.7 (14h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85857
telemt_connections_bad_total 2743
telemt_handshake_timeouts_total 7521
telemt_upstream_connect_attempt_total 14711
telemt_upstream_connect_success_total 14711
telemt_upstream_connect_attempts_per_request{bucket="1"} 14711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 14337
telemt_me_reconnect_success_total 11996
telemt_me_reader_eof_total 12846
telemt_me_idle_close_by_peer_total 12846
telemt_me_route_drop_no_conn_total 36928
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72951
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 12203
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 11980
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 72948
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 1466461064 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 35864171464 (33.40 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 53496.4 (14h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88845
telemt_connections_bad_total 1609
telemt_handshake_timeouts_total 2700
telemt_upstream_connect_attempt_total 15539
telemt_upstream_connect_success_total 15531
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 15539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 14964
telemt_me_reconnect_success_total 12815
telemt_me_reader_eof_total 13723
telemt_me_idle_close_by_peer_total 13723
telemt_me_route_drop_no_conn_total 34056
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80682
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
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 13005
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 12807
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 80595
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 9900274560 (9.22 GB)
telemt_user_octets_to_client{user="hello"} 49852268084 (46.43 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 53496.1 (14h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120984
telemt_connections_bad_total 398
telemt_handshake_timeouts_total 768
telemt_upstream_connect_attempt_total 12560
telemt_upstream_connect_success_total 12558
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 12560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9931
telemt_me_reconnect_success_total 9872
telemt_me_reader_eof_total 10527
telemt_me_idle_close_by_peer_total 10527
telemt_me_route_drop_no_conn_total 47586
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110261
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 316
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9982
telemt_me_writer_restored_same_endpoint_total 9861
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 110180
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 1952722756 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 58566345116 (54.54 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 28567.4 (7h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69680
telemt_connections_bad_total 20154
telemt_handshake_timeouts_total 1353
telemt_upstream_connect_attempt_total 9124
telemt_upstream_connect_success_total 9062
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 9124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4955
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 101875
telemt_me_reconnect_success_total 7454
telemt_me_reader_eof_total 7768
telemt_me_idle_close_by_peer_total 7768
telemt_me_route_drop_no_conn_total 23036
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46645
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
telemt_me_writer_removed_unexpected_total 7450
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 7350
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 46782
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 726891909 (693.22 MB)
telemt_user_octets_to_client{user="hello"} 18425713635 (17.16 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 53495.3 (14h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313177
telemt_connections_bad_total 47821
telemt_handshake_timeouts_total 2515
telemt_upstream_connect_attempt_total 11431
telemt_upstream_connect_success_total 11362
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 11431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 8723
telemt_me_reconnect_success_total 8662
telemt_me_reader_eof_total 9206
telemt_me_idle_close_by_peer_total 9206
telemt_me_route_drop_no_conn_total 139939
telemt_me_route_drop_channel_closed_total 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253621
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 220
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8741
telemt_me_writer_restored_same_endpoint_total 8635
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 251981
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 5175491400 (4.82 GB)
telemt_user_octets_to_client{user="hello"} 119654416420 (111.44 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 71
```