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

# Server Metrics 2026-03-16 18:38:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 18009.2 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175856
telemt_connections_bad_total 873
telemt_handshake_timeouts_total 4444
telemt_upstream_connect_attempt_total 3727
telemt_upstream_connect_success_total 3714
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3953
telemt_me_reconnect_success_total 2783
telemt_me_reader_eof_total 2898
telemt_me_idle_close_by_peer_total 2897
telemt_me_route_drop_no_conn_total 55001
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164753
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 842
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 646
telemt_desync_frames_bucket_total{bucket="1_2"} 312
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2843
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2781
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 164666
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 3155306884 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 93903571560 (87.45 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 12787.7 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87707
telemt_connections_bad_total 645
telemt_handshake_timeouts_total 3304
telemt_upstream_connect_attempt_total 2745
telemt_upstream_connect_success_total 2730
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 236
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 5534
telemt_me_reconnect_success_total 2024
telemt_me_reader_eof_total 2180
telemt_me_idle_close_by_peer_total 2180
telemt_me_route_drop_no_conn_total 48954
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80663
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2167
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 2019
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 80604
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 923431796 (880.65 MB)
telemt_user_octets_to_client{user="hello"} 22867379712 (21.30 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 18122.2 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72484
telemt_connections_bad_total 94
telemt_handshake_timeouts_total 919
telemt_upstream_connect_attempt_total 5213
telemt_upstream_connect_success_total 5158
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 5213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 42085
telemt_me_reconnect_success_total 3198
telemt_me_reader_eof_total 3573
telemt_me_idle_close_by_peer_total 3573
telemt_me_route_drop_no_conn_total 25688
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67206
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 166
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3537
telemt_me_refill_failed_total 1214
telemt_me_writer_restored_same_endpoint_total 3154
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 68138
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 918343006 (875.80 MB)
telemt_user_octets_to_client{user="hello"} 19982299062 (18.61 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 18258.5 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140009
telemt_connections_bad_total 249
telemt_handshake_timeouts_total 1907
telemt_upstream_connect_attempt_total 3925
telemt_upstream_connect_success_total 3898
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 3925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1994
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9249
telemt_me_reconnect_success_total 2890
telemt_me_reader_eof_total 3166
telemt_me_idle_close_by_peer_total 3165
telemt_me_route_drop_no_conn_total 50963
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132922
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 678
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 484
telemt_desync_frames_bucket_total{bucket="1_2"} 118
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 3126
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 2886
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 132889
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 1846857316 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 33688148816 (31.37 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 15718.9 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78232
telemt_connections_bad_total 20802
telemt_handshake_timeouts_total 593
telemt_upstream_connect_attempt_total 4193
telemt_upstream_connect_success_total 4132
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 4193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 4964
telemt_me_reconnect_success_total 3300
telemt_me_reader_eof_total 3431
telemt_me_idle_close_by_peer_total 3431
telemt_me_route_drop_no_conn_total 53050
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73002
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 73
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3459
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 3300
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 54042
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 2118396628 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 35247560048 (32.83 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 17826.1 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207249
telemt_connections_bad_total 5673
telemt_handshake_timeouts_total 3476
telemt_upstream_connect_attempt_total 3591
telemt_upstream_connect_success_total 3591
telemt_upstream_connect_attempts_per_request{bucket="1"} 3591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7688
telemt_me_reconnect_success_total 2657
telemt_me_reader_eof_total 2887
telemt_me_idle_close_by_peer_total 2886
telemt_me_route_drop_no_conn_total 95867
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189955
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 146
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2837
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 2651
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 189555
telemt_user_connections_current{user="hello"} 739
telemt_user_octets_from_client{user="hello"} 3703152600 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 68650287096 (63.94 GB)
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 94
```