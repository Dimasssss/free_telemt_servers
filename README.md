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

# Server Metrics 2026-03-15 16:14:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 64828.5 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297098
telemt_connections_bad_total 2789
telemt_handshake_timeouts_total 9009
telemt_upstream_connect_attempt_total 16051
telemt_upstream_connect_success_total 15968
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 16051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16126
telemt_me_reconnect_success_total 12738
telemt_me_reader_eof_total 13567
telemt_me_idle_close_by_peer_total 13567
telemt_me_route_drop_no_conn_total 450982
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334601
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1768
telemt_desync_full_logged_total 708
telemt_desync_suppressed_total 1060
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 696
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 12977
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12704
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 273705
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 5823206920 (5.42 GB)
telemt_user_octets_to_client{user="hello"} 226071637268 (210.55 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 64835.3 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114935
telemt_connections_bad_total 2815
telemt_handshake_timeouts_total 10887
telemt_upstream_connect_attempt_total 17809
telemt_upstream_connect_success_total 17809
telemt_upstream_connect_attempts_per_request{bucket="1"} 17809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 16897
telemt_me_reconnect_success_total 14537
telemt_me_reader_eof_total 15526
telemt_me_idle_close_by_peer_total 15526
telemt_me_route_drop_no_conn_total 47399
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97830
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
telemt_me_writer_removed_unexpected_total 14782
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 14521
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 97814
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 1887277132 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 49140137472 (45.77 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 64827.7 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121312
telemt_connections_bad_total 1664
telemt_handshake_timeouts_total 3054
telemt_upstream_connect_attempt_total 19357
telemt_upstream_connect_success_total 19349
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 19357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 23414
telemt_me_reconnect_success_total 16062
telemt_me_reader_eof_total 17206
telemt_me_idle_close_by_peer_total 17206
telemt_me_route_drop_no_conn_total 47035
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105546
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
telemt_me_writer_removed_unexpected_total 16440
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 16054
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 378
telemt_user_connections_total{user="hello"} 105443
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 10418148172 (9.70 GB)
telemt_user_octets_to_client{user="hello"} 60748558348 (56.58 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 64827.3 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162313
telemt_connections_bad_total 885
telemt_handshake_timeouts_total 988
telemt_upstream_connect_attempt_total 15582
telemt_upstream_connect_success_total 15573
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 12420
telemt_me_reconnect_success_total 12342
telemt_me_reader_eof_total 13128
telemt_me_idle_close_by_peer_total 13128
telemt_me_route_drop_no_conn_total 63295
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149364
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 524
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 344
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 12489
telemt_me_writer_restored_same_endpoint_total 12331
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 149277
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 2825115436 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 69856610728 (65.06 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 39898.8 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97883
telemt_connections_bad_total 22582
telemt_handshake_timeouts_total 2185
telemt_upstream_connect_attempt_total 12483
telemt_upstream_connect_success_total 12411
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 12483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 104652
telemt_me_reconnect_success_total 10213
telemt_me_reader_eof_total 10697
telemt_me_idle_close_by_peer_total 10697
telemt_me_route_drop_no_conn_total 33537
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70739
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 10262
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 10109
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 70875
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 1109948537 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 28975786891 (26.99 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 64829.6 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 412727
telemt_connections_bad_total 52150
telemt_handshake_timeouts_total 3464
telemt_upstream_connect_attempt_total 14038
telemt_upstream_connect_success_total 13956
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 14038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7060
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 11996
telemt_me_reconnect_success_total 10696
telemt_me_reader_eof_total 11356
telemt_me_idle_close_by_peer_total 11356
telemt_me_route_drop_no_conn_total 239970
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366981
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 309
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10844
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 10669
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 342144
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 9181756388 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 179768197944 (167.42 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 76
```