# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
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

## rdp-onedash.ru (2 сервера)
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

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-21 13:05:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 59386.6 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1948605
telemt_connections_bad_total 97751
telemt_connections_current 1730
telemt_connections_me_current 1730
telemt_handshake_timeouts_total 71718
telemt_upstream_connect_attempt_total 22878
telemt_upstream_connect_success_total 22764
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 22840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14609
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1267
telemt_me_reconnect_success_total 524
telemt_me_reader_eof_total 507
telemt_me_idle_close_by_peer_total 507
telemt_me_route_drop_no_conn_total 1463467
telemt_me_route_drop_channel_closed_total 481
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1531721
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 415
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 467
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 5967
telemt_desync_full_logged_total 2078
telemt_desync_suppressed_total 3889
telemt_desync_frames_bucket_total{bucket="1_2"} 1298
telemt_desync_frames_bucket_total{bucket="3_10"} 2284
telemt_desync_frames_bucket_total{bucket="gt_10"} 2385
telemt_pool_swap_total 64
telemt_pool_force_close_total 1874
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 359
telemt_me_draining_writers_reap_progress_total 20437
telemt_me_writer_removed_unexpected_total 488
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1686
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19091
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1809
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18563
telemt_me_writer_teardown_success_total{mode="normal"} 20777
telemt_me_writer_teardown_noop_total 20441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41218
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 156.786269
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41218
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 359
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 454
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 1530614
telemt_user_connections_current{user="hello"} 1730
telemt_user_octets_from_client{user="hello"} 22794014103 (21.23 GB)
telemt_user_octets_to_client{user="hello"} 398089591779 (370.75 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 615
telemt_user_unique_ips_recent_window{user="hello"} 296
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 5032.0 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350733
telemt_connections_bad_total 19443
telemt_connections_current 2996
telemt_connections_me_current 2996
telemt_handshake_timeouts_total 18156
telemt_upstream_connect_attempt_total 2195
telemt_upstream_connect_success_total 2131
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 2177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1216
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 193
telemt_me_reconnect_success_total 132
telemt_me_reader_eof_total 119
telemt_me_idle_close_by_peer_total 119
telemt_me_route_drop_no_conn_total 295102
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290729
telemt_me_endpoint_quarantine_total 38
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 50
telemt_desync_total 1024
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 550
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 418
telemt_desync_frames_bucket_total{bucket="gt_10"} 398
telemt_pool_swap_total 3
telemt_pool_force_close_total 131
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 9
telemt_me_draining_writers_reap_progress_total 1806
telemt_me_writer_removed_unexpected_total 127
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 233
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1700
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1675
telemt_me_writer_teardown_success_total{mode="normal"} 1933
telemt_me_writer_teardown_noop_total 1806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.912406
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 9
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 121
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 290536
telemt_user_connections_current{user="hello"} 2996
telemt_user_octets_from_client{user="hello"} 4284724832 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 75701411984 (70.50 GB)
telemt_user_unique_ips_current{user="hello"} 1346
telemt_user_unique_ips_recent_window{user="hello"} 932
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 59384.6 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3796988
telemt_connections_bad_total 385749
telemt_connections_current 5109
telemt_connections_me_current 5109
telemt_handshake_timeouts_total 147413
telemt_upstream_connect_attempt_total 22338
telemt_upstream_connect_success_total 22304
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 22309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 818
telemt_me_reconnect_success_total 456
telemt_me_reader_eof_total 466
telemt_me_idle_close_by_peer_total 466
telemt_me_route_drop_no_conn_total 1839574
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3043994
telemt_me_endpoint_quarantine_total 376
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 453
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 13000
telemt_desync_full_logged_total 4406
telemt_desync_suppressed_total 8594
telemt_desync_frames_bucket_total{bucket="1_2"} 2761
telemt_desync_frames_bucket_total{bucket="3_10"} 5082
telemt_desync_frames_bucket_total{bucket="gt_10"} 5157
telemt_pool_swap_total 63
telemt_pool_force_close_total 1986
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 295
telemt_me_draining_writers_reap_progress_total 20295
telemt_me_writer_removed_unexpected_total 449
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1721
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18845
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1842
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 144
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18309
telemt_me_writer_teardown_success_total{mode="normal"} 20566
telemt_me_writer_teardown_noop_total 20311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40877
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 58.500084
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40877
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 295
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 412
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 3040123
telemt_user_connections_current{user="hello"} 5109
telemt_user_octets_from_client{user="hello"} 49555316252 (46.15 GB)
telemt_user_octets_to_client{user="hello"} 1060504339240 (987.67 GB)
telemt_user_unique_ips_current{user="hello"} 1843
telemt_user_unique_ips_recent_window{user="hello"} 864
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 59385.9 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3108425
telemt_connections_bad_total 337425
telemt_connections_current 4368
telemt_connections_me_current 4368
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 121119
telemt_upstream_connect_attempt_total 27032
telemt_upstream_connect_success_total 26759
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 26892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12325
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 476
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1145
telemt_me_reconnect_success_total 529
telemt_me_reader_eof_total 492
telemt_me_idle_close_by_peer_total 492
telemt_me_route_drop_no_conn_total 972737
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2235465
telemt_me_endpoint_quarantine_total 391
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 454
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 10300
telemt_desync_full_logged_total 3485
telemt_desync_suppressed_total 6815
telemt_desync_frames_bucket_total{bucket="1_2"} 2568
telemt_desync_frames_bucket_total{bucket="3_10"} 3977
telemt_desync_frames_bucket_total{bucket="gt_10"} 3755
telemt_pool_swap_total 64
telemt_pool_force_close_total 1793
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 19770
telemt_me_writer_removed_unexpected_total 479
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1667
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18603
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1675
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 118
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17977
telemt_me_writer_teardown_success_total{mode="normal"} 20270
telemt_me_writer_teardown_noop_total 19771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40041
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.458587
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40041
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 444
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2236436
telemt_user_connections_current{user="hello"} 4368
telemt_user_octets_from_client{user="hello"} 42120159689 (39.23 GB)
telemt_user_octets_to_client{user="hello"} 1058326971763 (985.64 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1619
telemt_user_unique_ips_recent_window{user="hello"} 637
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 59349.9 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3036918
telemt_connections_bad_total 330168
telemt_connections_current 3584
telemt_connections_me_current 3584
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 88351
telemt_upstream_connect_attempt_total 32234
telemt_upstream_connect_success_total 32011
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 32144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13654
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 839
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1271
telemt_me_reconnect_success_total 611
telemt_me_reader_eof_total 554
telemt_me_idle_close_by_peer_total 554
telemt_me_route_drop_no_conn_total 922113
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2208534
telemt_me_endpoint_quarantine_total 435
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 447
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 48
telemt_desync_total 10219
telemt_desync_full_logged_total 3417
telemt_desync_suppressed_total 6802
telemt_desync_frames_bucket_total{bucket="1_2"} 2625
telemt_desync_frames_bucket_total{bucket="3_10"} 3893
telemt_desync_frames_bucket_total{bucket="gt_10"} 3701
telemt_pool_swap_total 62
telemt_pool_force_close_total 1743
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 204
telemt_me_draining_writers_reap_progress_total 21127
telemt_me_writer_removed_unexpected_total 528
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1783
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19906
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1588
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 155
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19384
telemt_me_writer_teardown_success_total{mode="normal"} 21689
telemt_me_writer_teardown_noop_total 21131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42820
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.317473
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42820
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 204
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 532
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2213619
telemt_user_connections_current{user="hello"} 3584
telemt_user_octets_from_client{user="hello"} 49518766445 (46.12 GB)
telemt_user_octets_to_client{user="hello"} 1052976672568 (980.66 GB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1383
telemt_user_unique_ips_recent_window{user="hello"} 635
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 59389.2 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10163333
telemt_connections_bad_total 688618
telemt_connections_current 6169
telemt_connections_me_current 6169
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 330851
telemt_upstream_connect_attempt_total 89395
telemt_upstream_connect_success_total 84196
telemt_upstream_connect_fail_total 4327
telemt_upstream_connect_attempts_per_request{bucket="1"} 88523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20167
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4327
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 3489
telemt_me_reconnect_success_total 1184
telemt_me_reader_eof_total 837
telemt_me_idle_close_by_peer_total 836
telemt_me_route_drop_no_conn_total 18598369
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8369691
telemt_me_endpoint_quarantine_total 449
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 466
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 15880
telemt_desync_full_logged_total 5063
telemt_desync_suppressed_total 10817
telemt_desync_frames_bucket_total{bucket="1_2"} 3380
telemt_desync_frames_bucket_total{bucket="3_10"} 6980
telemt_desync_frames_bucket_total{bucket="gt_10"} 5520
telemt_pool_swap_total 60
telemt_pool_force_close_total 1906
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 393
telemt_me_draining_writers_reap_progress_total 19303
telemt_me_writer_removed_unexpected_total 1146
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2494
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17838
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1632
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17397
telemt_me_writer_teardown_success_total{mode="normal"} 20332
telemt_me_writer_teardown_noop_total 19312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39644
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.363026
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39644
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 393
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 824
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 8427341
telemt_user_connections_current{user="hello"} 6169
telemt_user_octets_from_client{user="hello"} 65192193737 (60.71 GB)
telemt_user_octets_to_client{user="hello"} 704579346680 (656.19 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 2129
telemt_user_unique_ips_recent_window{user="hello"} 1324
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 59356.9 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3064382
telemt_connections_bad_total 362840
telemt_connections_current 4061
telemt_connections_me_current 4061
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 67322
telemt_upstream_connect_attempt_total 25368
telemt_upstream_connect_success_total 25088
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 25338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_reconnect_attempts_total 2477
telemt_me_reconnect_success_total 851
telemt_me_reader_eof_total 842
telemt_me_idle_close_by_peer_total 842
telemt_me_route_drop_no_conn_total 1135341
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2324186
telemt_me_endpoint_quarantine_total 374
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 452
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 10809
telemt_desync_full_logged_total 3768
telemt_desync_suppressed_total 7041
telemt_desync_frames_bucket_total{bucket="1_2"} 2116
telemt_desync_frames_bucket_total{bucket="3_10"} 4318
telemt_desync_frames_bucket_total{bucket="gt_10"} 4375
telemt_pool_swap_total 60
telemt_pool_force_close_total 1687
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 156
telemt_me_draining_writers_reap_progress_total 21173
telemt_me_writer_removed_unexpected_total 814
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2029
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19986
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1497
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 190
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19486
telemt_me_writer_teardown_success_total{mode="normal"} 22015
telemt_me_writer_teardown_noop_total 21174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43189
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.476564
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43189
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 156
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 716
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 2308956
telemt_user_connections_current{user="hello"} 4061
telemt_user_octets_from_client{user="hello"} 45459488916 (42.34 GB)
telemt_user_octets_to_client{user="hello"} 1010968652954 (941.54 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1592
telemt_user_unique_ips_recent_window{user="hello"} 664
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 59351.5 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4661282
telemt_connections_bad_total 232285
telemt_connections_current 3943
telemt_connections_me_current 3943
telemt_handshake_timeouts_total 2057487
telemt_upstream_connect_attempt_total 23588
telemt_upstream_connect_success_total 23554
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 23557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 986
telemt_me_reconnect_success_total 423
telemt_me_reader_eof_total 431
telemt_me_idle_close_by_peer_total 431
telemt_me_route_drop_no_conn_total 1022016
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2083310
telemt_me_endpoint_quarantine_total 444
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 462
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 9933
telemt_desync_full_logged_total 3530
telemt_desync_suppressed_total 6403
telemt_desync_frames_bucket_total{bucket="1_2"} 1825
telemt_desync_frames_bucket_total{bucket="3_10"} 3940
telemt_desync_frames_bucket_total{bucket="gt_10"} 4168
telemt_pool_swap_total 64
telemt_pool_force_close_total 1628
telemt_me_writer_close_signal_drop_total 139
telemt_me_draining_writers_reap_progress_total 21106
telemt_me_writer_removed_unexpected_total 413
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1439
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20107
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1573
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19478
telemt_me_writer_teardown_success_total{mode="normal"} 21546
telemt_me_writer_teardown_noop_total 21106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42652
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.399433
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42652
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 139
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 368
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2076663
telemt_user_connections_current{user="hello"} 3943
telemt_user_octets_from_client{user="hello"} 38344361880 (35.71 GB)
telemt_user_octets_to_client{user="hello"} 980927186224 (913.56 GB)
telemt_user_unique_ips_current{user="hello"} 1495
telemt_user_unique_ips_recent_window{user="hello"} 667
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 57342.7 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 995330
telemt_connections_bad_total 115508
telemt_connections_current 786
telemt_connections_me_current 786
telemt_handshake_timeouts_total 350718
telemt_upstream_connect_attempt_total 27104
telemt_upstream_connect_success_total 27102
telemt_upstream_connect_attempts_per_request{bucket="1"} 27102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1150
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 447
telemt_me_idle_close_by_peer_total 447
telemt_me_route_drop_no_conn_total 206744
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 460417
telemt_me_endpoint_quarantine_total 530
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 485
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 3130
telemt_desync_full_logged_total 1166
telemt_desync_suppressed_total 1964
telemt_desync_frames_bucket_total{bucket="1_2"} 544
telemt_desync_frames_bucket_total{bucket="3_10"} 1112
telemt_desync_frames_bucket_total{bucket="gt_10"} 1474
telemt_pool_swap_total 63
telemt_pool_force_close_total 1416
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 24299
telemt_me_writer_removed_unexpected_total 424
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1781
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22950
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1413
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22883
telemt_me_writer_teardown_success_total{mode="normal"} 24731
telemt_me_writer_teardown_noop_total 24299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49030
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.202427
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49030
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 367
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 460227
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 7502364259 (6.99 GB)
telemt_user_octets_to_client{user="hello"} 176257256609 (164.15 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 59361.1 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3298183
telemt_connections_bad_total 317808
telemt_connections_current 4511
telemt_connections_me_current 4511
telemt_handshake_timeouts_total 97355
telemt_upstream_connect_attempt_total 24396
telemt_upstream_connect_success_total 24296
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 24365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12187
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 975
telemt_me_reconnect_success_total 552
telemt_me_reader_eof_total 516
telemt_me_idle_close_by_peer_total 516
telemt_me_route_drop_no_conn_total 915882
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2597318
telemt_me_endpoint_quarantine_total 453
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 457
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 10594
telemt_desync_full_logged_total 3484
telemt_desync_suppressed_total 7110
telemt_desync_frames_bucket_total{bucket="1_2"} 2523
telemt_desync_frames_bucket_total{bucket="3_10"} 3949
telemt_desync_frames_bucket_total{bucket="gt_10"} 4122
telemt_pool_swap_total 65
telemt_pool_force_close_total 1672
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 180
telemt_me_draining_writers_reap_progress_total 21919
telemt_me_writer_removed_unexpected_total 507
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1690
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20734
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1642
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20247
telemt_me_writer_teardown_success_total{mode="normal"} 22424
telemt_me_writer_teardown_noop_total 21919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44343
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.594272
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44343
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 180
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 492
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 2590225
telemt_user_connections_current{user="hello"} 4511
telemt_user_octets_from_client{user="hello"} 54913430884 (51.14 GB)
telemt_user_octets_to_client{user="hello"} 1219262733820 (1.11 TB)
telemt_user_unique_ips_current{user="hello"} 1663
telemt_user_unique_ips_recent_window{user="hello"} 753
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 59358.2 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2968696
telemt_connections_bad_total 246652
telemt_connections_current 4219
telemt_connections_me_current 4219
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 86119
telemt_upstream_connect_attempt_total 40642
telemt_upstream_connect_success_total 40382
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 40597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13881
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 586
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_reconnect_attempts_total 3422
telemt_me_reconnect_success_total 733
telemt_me_reader_eof_total 634
telemt_me_idle_close_by_peer_total 634
telemt_me_seq_mismatch_total 30
telemt_me_route_drop_no_conn_total 966276
telemt_me_route_drop_channel_closed_total 72
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2385395
telemt_me_endpoint_quarantine_total 510
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 456
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 9214
telemt_desync_full_logged_total 3133
telemt_desync_suppressed_total 6081
telemt_desync_frames_bucket_total{bucket="1_2"} 2375
telemt_desync_frames_bucket_total{bucket="3_10"} 3389
telemt_desync_frames_bucket_total{bucket="gt_10"} 3450
telemt_pool_swap_total 64
telemt_pool_force_close_total 1618
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 21128
telemt_me_writer_removed_unexpected_total 647
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1994
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19810
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1510
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19510
telemt_me_writer_teardown_success_total{mode="normal"} 21804
telemt_me_writer_teardown_noop_total 21129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42933
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.612457
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42933
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 557
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2395429
telemt_user_connections_current{user="hello"} 4219
telemt_user_octets_from_client{user="hello"} 44282614057 (41.24 GB)
telemt_user_octets_to_client{user="hello"} 1049904456192 (977.80 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1568
telemt_user_unique_ips_recent_window{user="hello"} 617
```