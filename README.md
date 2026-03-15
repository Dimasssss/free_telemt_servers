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

# Server Metrics 2026-03-15 11:44:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 48598.0 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209144
telemt_connections_bad_total 1392
telemt_handshake_timeouts_total 4563
telemt_upstream_connect_attempt_total 12352
telemt_upstream_connect_success_total 12287
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 12352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6836
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13239
telemt_me_reconnect_success_total 9870
telemt_me_reader_eof_total 10546
telemt_me_idle_close_by_peer_total 10546
telemt_me_route_drop_no_conn_total 420903
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255949
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1478
telemt_desync_full_logged_total 589
telemt_desync_suppressed_total 889
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 586
telemt_desync_frames_bucket_total{bucket="gt_10"} 649
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 10074
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 9839
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 195206
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 3680852492 (3.43 GB)
telemt_user_octets_to_client{user="hello"} 189264141352 (176.27 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 48604.3 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70655
telemt_connections_bad_total 2337
telemt_handshake_timeouts_total 3912
telemt_upstream_connect_attempt_total 13250
telemt_upstream_connect_success_total 13250
telemt_upstream_connect_attempts_per_request{bucket="1"} 13250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 13139
telemt_me_reconnect_success_total 10807
telemt_me_reader_eof_total 11565
telemt_me_idle_close_by_peer_total 11565
telemt_me_route_drop_no_conn_total 32874
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62055
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10995
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 10791
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 62054
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 1140776592 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 25850929280 (24.08 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 48596.8 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77086
telemt_connections_bad_total 1012
telemt_handshake_timeouts_total 2558
telemt_upstream_connect_attempt_total 13859
telemt_upstream_connect_success_total 13851
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 13859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 13550
telemt_me_reconnect_success_total 11414
telemt_me_reader_eof_total 12226
telemt_me_idle_close_by_peer_total 12226
telemt_me_route_drop_no_conn_total 29428
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70169
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 11589
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 11406
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 70086
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 9490175040 (8.84 GB)
telemt_user_octets_to_client{user="hello"} 43056897956 (40.10 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 48596.6 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103595
telemt_connections_bad_total 364
telemt_handshake_timeouts_total 688
telemt_upstream_connect_attempt_total 11439
telemt_upstream_connect_success_total 11438
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9075
telemt_me_reconnect_success_total 9030
telemt_me_reader_eof_total 9636
telemt_me_idle_close_by_peer_total 9636
telemt_me_route_drop_no_conn_total 41532
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94511
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 238
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9129
telemt_me_writer_restored_same_endpoint_total 9019
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 94432
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 1712810132 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 53796898444 (50.10 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 23668.1 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53470
telemt_connections_bad_total 14253
telemt_handshake_timeouts_total 848
telemt_upstream_connect_attempt_total 7872
telemt_upstream_connect_success_total 7814
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 7872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4257
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 100848
telemt_me_reconnect_success_total 6433
telemt_me_reader_eof_total 6690
telemt_me_idle_close_by_peer_total 6690
telemt_me_route_drop_no_conn_total 18731
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37150
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 70
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 6419
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6329
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 37287
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 555623809 (529.88 MB)
telemt_user_octets_to_client{user="hello"} 14530158195 (13.53 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 48596.0 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274358
telemt_connections_bad_total 47646
telemt_handshake_timeouts_total 2029
telemt_upstream_connect_attempt_total 10258
telemt_upstream_connect_success_total 10196
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 10258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 7824
telemt_me_reconnect_success_total 7774
telemt_me_reader_eof_total 8283
telemt_me_idle_close_by_peer_total 8283
telemt_me_route_drop_no_conn_total 121309
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216702
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 120
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7838
telemt_me_writer_restored_same_endpoint_total 7747
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 215066
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 4798221656 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 102116062940 (95.10 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 80
```