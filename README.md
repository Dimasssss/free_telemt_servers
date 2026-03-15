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

# Server Metrics 2026-03-15 16:04:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 64215.8 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293965
telemt_connections_bad_total 2789
telemt_handshake_timeouts_total 8987
telemt_upstream_connect_attempt_total 15979
telemt_upstream_connect_success_total 15896
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8841
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16059
telemt_me_reconnect_success_total 12672
telemt_me_reader_eof_total 13498
telemt_me_idle_close_by_peer_total 13498
telemt_me_route_drop_no_conn_total 450012
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 331566
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1761
telemt_desync_full_logged_total 705
telemt_desync_suppressed_total 1056
telemt_desync_frames_bucket_total{bucket="1_2"} 317
telemt_desync_frames_bucket_total{bucket="3_10"} 695
telemt_desync_frames_bucket_total{bucket="gt_10"} 749
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 12909
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12638
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 270669
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 5773939052 (5.38 GB)
telemt_user_octets_to_client{user="hello"} 224768717344 (209.33 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 64222.7 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112992
telemt_connections_bad_total 2815
telemt_handshake_timeouts_total 10778
telemt_upstream_connect_attempt_total 17682
telemt_upstream_connect_success_total 17682
telemt_upstream_connect_attempts_per_request{bucket="1"} 17682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 16774
telemt_me_reconnect_success_total 14414
telemt_me_reader_eof_total 15400
telemt_me_idle_close_by_peer_total 15400
telemt_me_route_drop_no_conn_total 46482
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96025
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14657
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 14398
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 96009
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 1867323528 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 48563339068 (45.23 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 64215.0 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119790
telemt_connections_bad_total 1664
telemt_handshake_timeouts_total 3048
telemt_upstream_connect_attempt_total 19097
telemt_upstream_connect_success_total 19089
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 19097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 23160
telemt_me_reconnect_success_total 15808
telemt_me_reader_eof_total 16949
telemt_me_idle_close_by_peer_total 16949
telemt_me_route_drop_no_conn_total 46329
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104070
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
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 16185
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 15800
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 377
telemt_user_connections_total{user="hello"} 103967
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 10395470688 (9.68 GB)
telemt_user_octets_to_client{user="hello"} 60276016588 (56.14 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 64214.6 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160259
telemt_connections_bad_total 885
telemt_handshake_timeouts_total 978
telemt_upstream_connect_attempt_total 15512
telemt_upstream_connect_success_total 15503
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 12356
telemt_me_reconnect_success_total 12278
telemt_me_reader_eof_total 13059
telemt_me_idle_close_by_peer_total 13059
telemt_me_route_drop_no_conn_total 62343
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147373
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 521
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 343
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 12425
telemt_me_writer_restored_same_endpoint_total 12267
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 147286
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 2808927812 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 69410097256 (64.64 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 39286.0 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96302
telemt_connections_bad_total 22473
telemt_handshake_timeouts_total 2177
telemt_upstream_connect_attempt_total 12262
telemt_upstream_connect_success_total 12190
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 12262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 104476
telemt_me_reconnect_success_total 10038
telemt_me_reader_eof_total 10496
telemt_me_idle_close_by_peer_total 10496
telemt_me_route_drop_no_conn_total 32907
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69349
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 162
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 10085
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 9934
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 69485
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 1100955665 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 28545466403 (26.59 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 64215.1 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405642
telemt_connections_bad_total 51444
telemt_handshake_timeouts_total 3409
telemt_upstream_connect_attempt_total 13885
telemt_upstream_connect_success_total 13803
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 13885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 11849
telemt_me_reconnect_success_total 10550
telemt_me_reader_eof_total 11208
telemt_me_idle_close_by_peer_total 11208
telemt_me_route_drop_no_conn_total 233076
telemt_me_route_drop_channel_closed_total 54
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 359800
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 307
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10696
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 10523
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 336140
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 9004876244 (8.39 GB)
telemt_user_octets_to_client{user="hello"} 176381502156 (164.27 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 102
```