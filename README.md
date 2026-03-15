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

# Server Metrics 2026-03-15 16:45:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 66667.3 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307179
telemt_connections_bad_total 2797
telemt_handshake_timeouts_total 9144
telemt_upstream_connect_attempt_total 16392
telemt_upstream_connect_success_total 16307
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 16392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16356
telemt_me_reconnect_success_total 12967
telemt_me_reader_eof_total 13814
telemt_me_idle_close_by_peer_total 13814
telemt_me_route_drop_no_conn_total 454294
telemt_me_route_drop_channel_closed_total 75
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344139
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1773
telemt_desync_full_logged_total 711
telemt_desync_suppressed_total 1062
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 700
telemt_desync_frames_bucket_total{bucket="gt_10"} 752
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13210
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12933
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 283242
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 5942022144 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 231786472852 (215.87 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 66674.3 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120386
telemt_connections_bad_total 2821
telemt_handshake_timeouts_total 11241
telemt_upstream_connect_attempt_total 18361
telemt_upstream_connect_success_total 18361
telemt_upstream_connect_attempts_per_request{bucket="1"} 18361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 17335
telemt_me_reconnect_success_total 14972
telemt_me_reader_eof_total 15992
telemt_me_idle_close_by_peer_total 15991
telemt_me_route_drop_no_conn_total 49676
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102777
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 15229
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 14956
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 102761
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 2038780788 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 50917218644 (47.42 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 66666.6 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125991
telemt_connections_bad_total 1665
telemt_handshake_timeouts_total 3105
telemt_upstream_connect_attempt_total 19863
telemt_upstream_connect_success_total 19855
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 19863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 23810
telemt_me_reconnect_success_total 16455
telemt_me_reader_eof_total 17643
telemt_me_idle_close_by_peer_total 17643
telemt_me_route_drop_no_conn_total 49059
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110031
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16841
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 16447
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 109926
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 10466517876 (9.75 GB)
telemt_user_octets_to_client{user="hello"} 62818449940 (58.50 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 66666.4 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169712
telemt_connections_bad_total 916
telemt_handshake_timeouts_total 1043
telemt_upstream_connect_attempt_total 15987
telemt_upstream_connect_success_total 15976
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 15987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 12715
telemt_me_reconnect_success_total 12635
telemt_me_reader_eof_total 13440
telemt_me_idle_close_by_peer_total 13440
telemt_me_route_drop_no_conn_total 66123
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156157
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 544
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 352
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 12789
telemt_me_writer_restored_same_endpoint_total 12624
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 156070
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 2920078056 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 71359825212 (66.46 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 41737.7 (11h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103106
telemt_connections_bad_total 22912
telemt_handshake_timeouts_total 2301
telemt_upstream_connect_attempt_total 12883
telemt_upstream_connect_success_total 12810
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 12883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 104965
telemt_me_reconnect_success_total 10524
telemt_me_reader_eof_total 11033
telemt_me_idle_close_by_peer_total 11033
telemt_me_route_drop_no_conn_total 35256
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75332
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 188
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 10578
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 10420
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 75467
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 1284914657 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 30485978451 (28.39 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 66665.8 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 437021
telemt_connections_bad_total 57517
telemt_handshake_timeouts_total 3558
telemt_upstream_connect_attempt_total 14433
telemt_upstream_connect_success_total 14350
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 14433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 12283
telemt_me_reconnect_success_total 10981
telemt_me_reader_eof_total 11667
telemt_me_idle_close_by_peer_total 11667
telemt_me_route_drop_no_conn_total 258518
telemt_me_route_drop_channel_closed_total 63
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388625
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11137
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 10954
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 360100
telemt_user_connections_current{user="hello"} 712
telemt_user_octets_from_client{user="hello"} 9537123556 (8.88 GB)
telemt_user_octets_to_client{user="hello"} 191545812960 (178.39 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 82
```