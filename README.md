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

# Server Metrics 2026-03-15 23:23:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 90552.0 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 403266
telemt_connections_bad_total 5286
telemt_handshake_timeouts_total 14045
telemt_upstream_connect_attempt_total 21628
telemt_upstream_connect_success_total 21525
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 21628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11952
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 20438
telemt_me_reconnect_success_total 17031
telemt_me_reader_eof_total 18177
telemt_me_idle_close_by_peer_total 18177
telemt_me_route_drop_no_conn_total 488355
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429929
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2115
telemt_desync_full_logged_total 835
telemt_desync_suppressed_total 1280
telemt_desync_frames_bucket_total{bucket="1_2"} 409
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 894
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 17323
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 16997
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 368991
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 8045893656 (7.49 GB)
telemt_user_octets_to_client{user="hello"} 277120862712 (258.09 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 90558.6 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168489
telemt_connections_bad_total 2906
telemt_handshake_timeouts_total 14107
telemt_upstream_connect_attempt_total 24663
telemt_upstream_connect_success_total 24588
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 24663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 608
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 26570
telemt_me_reconnect_success_total 19674
telemt_me_reader_eof_total 21048
telemt_me_idle_close_by_peer_total 21047
telemt_me_route_drop_no_conn_total 68426
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144608
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 20183
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 19658
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 509
telemt_user_connections_total{user="hello"} 144877
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 3361888589 (3.13 GB)
telemt_user_octets_to_client{user="hello"} 76353857280 (71.11 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 90551.0 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167156
telemt_connections_bad_total 1768
telemt_handshake_timeouts_total 3514
telemt_upstream_connect_attempt_total 25804
telemt_upstream_connect_success_total 25796
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 25804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 28614
telemt_me_reconnect_success_total 21239
telemt_me_reader_eof_total 22835
telemt_me_idle_close_by_peer_total 22834
telemt_me_route_drop_no_conn_total 65921
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149234
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 21673
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 21231
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 434
telemt_user_connections_total{user="hello"} 149116
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 13086742568 (12.19 GB)
telemt_user_octets_to_client{user="hello"} 97359282688 (90.67 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 90550.8 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245262
telemt_connections_bad_total 1203
telemt_handshake_timeouts_total 1619
telemt_upstream_connect_attempt_total 21120
telemt_upstream_connect_success_total 21101
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 21120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10896
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 16705
telemt_me_reconnect_success_total 16605
telemt_me_reader_eof_total 17699
telemt_me_idle_close_by_peer_total 17699
telemt_me_route_drop_no_conn_total 89310
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226577
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 862
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 322
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 16800
telemt_me_writer_restored_same_endpoint_total 16594
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 226489
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 4093165484 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 106469877072 (99.16 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 65622.5 (18h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154252
telemt_connections_bad_total 28473
telemt_handshake_timeouts_total 2817
telemt_upstream_connect_attempt_total 18885
telemt_upstream_connect_success_total 18776
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 18885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 109808
telemt_me_reconnect_success_total 15349
telemt_me_reader_eof_total 16218
telemt_me_idle_close_by_peer_total 16218
telemt_me_route_drop_no_conn_total 49213
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118616
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 15461
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 15245
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 118742
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 1771043629 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 42659646079 (39.73 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 90550.2 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 609386
telemt_connections_bad_total 58577
telemt_handshake_timeouts_total 4725
telemt_upstream_connect_attempt_total 19133
telemt_upstream_connect_success_total 19027
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 19133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 15819
telemt_me_reconnect_success_total 14504
telemt_me_reader_eof_total 15443
telemt_me_idle_close_by_peer_total 15443
telemt_me_route_drop_no_conn_total 548644
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 646004
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 324
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14707
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 14477
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 510974
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 12485343916 (11.63 GB)
telemt_user_octets_to_client{user="hello"} 316388135056 (294.66 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 36
```