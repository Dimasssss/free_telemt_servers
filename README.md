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

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
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
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
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

# Server Metrics 2026-03-22 05:14:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 29274.0 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496190
telemt_connections_bad_total 33455
telemt_connections_current 1195
telemt_connections_me_current 1195
telemt_handshake_timeouts_total 26959
telemt_upstream_connect_attempt_total 12146
telemt_upstream_connect_success_total 12145
telemt_upstream_connect_attempts_per_request{bucket="1"} 12145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7838
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 321
telemt_me_reconnect_success_total 191
telemt_me_reader_eof_total 186
telemt_me_idle_close_by_peer_total 186
telemt_me_route_drop_no_conn_total 104807
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 409797
telemt_me_endpoint_quarantine_total 228
telemt_me_single_endpoint_shadow_rotate_total 245
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 3663
telemt_desync_full_logged_total 994
telemt_desync_suppressed_total 2669
telemt_desync_frames_bucket_total{bucket="1_2"} 1241
telemt_desync_frames_bucket_total{bucket="3_10"} 1402
telemt_desync_frames_bucket_total{bucket="gt_10"} 1020
telemt_pool_swap_total 32
telemt_pool_force_close_total 845
telemt_me_writer_close_signal_drop_total 72
telemt_me_draining_writers_reap_progress_total 10979
telemt_me_writer_removed_unexpected_total 184
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10404
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 840
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10134
telemt_me_writer_teardown_success_total{mode="normal"} 11153
telemt_me_writer_teardown_noop_total 10980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22133
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.667542
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22133
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 72
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 173
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 408841
telemt_user_connections_current{user="hello"} 1195
telemt_user_octets_from_client{user="hello"} 5543825144 (5.16 GB)
telemt_user_octets_to_client{user="hello"} 144161395320 (134.26 GB)
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 42641.0 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 949735
telemt_connections_bad_total 70719
telemt_connections_current 674
telemt_connections_me_current 674
telemt_handshake_timeouts_total 32410
telemt_upstream_connect_attempt_total 22877
telemt_upstream_connect_success_total 22558
telemt_upstream_connect_fail_total 288
telemt_upstream_connect_attempts_per_request{bucket="1"} 22846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10955
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 288
telemt_me_reconnect_attempts_total 1729
telemt_me_reconnect_success_total 629
telemt_me_reader_eof_total 550
telemt_me_idle_close_by_peer_total 550
telemt_me_route_drop_no_conn_total 370494
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 741926
telemt_me_endpoint_quarantine_total 406
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 348
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
telemt_me_writers_active_current 41
telemt_desync_total 3202
telemt_desync_full_logged_total 1844
telemt_desync_suppressed_total 1358
telemt_desync_frames_bucket_total{bucket="1_2"} 671
telemt_desync_frames_bucket_total{bucket="3_10"} 1232
telemt_desync_frames_bucket_total{bucket="gt_10"} 1299
telemt_pool_swap_total 46
telemt_pool_force_close_total 1206
telemt_me_writer_close_signal_drop_total 87
telemt_me_draining_writers_reap_progress_total 17694
telemt_me_writer_removed_unexpected_total 525
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1518
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16713
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16488
telemt_me_writer_teardown_success_total{mode="normal"} 18231
telemt_me_writer_teardown_noop_total 17694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35925
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.089132
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35925
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 87
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 470
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 743660
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 11913030711 (11.09 GB)
telemt_user_octets_to_client{user="hello"} 270800757034 (252.20 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 117500.3 (32h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8190933
telemt_connections_bad_total 706321
telemt_connections_current 2890
telemt_connections_me_current 2890
telemt_handshake_timeouts_total 267282
telemt_upstream_connect_attempt_total 43814
telemt_upstream_connect_success_total 43736
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 43744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1642
telemt_me_reconnect_success_total 858
telemt_me_reader_eof_total 866
telemt_me_idle_close_by_peer_total 866
telemt_me_route_drop_no_conn_total 4619678
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6581457
telemt_me_endpoint_quarantine_total 752
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 885
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 27752
telemt_desync_full_logged_total 9238
telemt_desync_suppressed_total 18514
telemt_desync_frames_bucket_total{bucket="1_2"} 5996
telemt_desync_frames_bucket_total{bucket="3_10"} 10859
telemt_desync_frames_bucket_total{bucket="gt_10"} 10897
telemt_pool_swap_total 127
telemt_pool_force_close_total 4174
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 631
telemt_me_draining_writers_reap_progress_total 40003
telemt_me_writer_removed_unexpected_total 834
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3308
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37058
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3930
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 244
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35829
telemt_me_writer_teardown_success_total{mode="normal"} 40366
telemt_me_writer_teardown_noop_total 40047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80413
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 166.426224
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80413
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 631
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 765
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6573038
telemt_user_connections_current{user="hello"} 2890
telemt_user_octets_from_client{user="hello"} 111436948832 (103.78 GB)
telemt_user_octets_to_client{user="hello"} 2226769539160 (2.03 TB)
telemt_user_unique_ips_current{user="hello"} 1261
telemt_user_unique_ips_recent_window{user="hello"} 425
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 117501.6 (32h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6750072
telemt_connections_bad_total 599816
telemt_connections_current 2686
telemt_connections_me_current 2686
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 224657
telemt_upstream_connect_attempt_total 47712
telemt_upstream_connect_success_total 47313
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 47515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2044
telemt_me_reconnect_success_total 922
telemt_me_reader_eof_total 899
telemt_me_idle_close_by_peer_total 899
telemt_me_route_drop_no_conn_total 2325172
telemt_me_route_drop_channel_closed_total 286
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5047710
telemt_me_endpoint_quarantine_total 743
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 908
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 23472
telemt_desync_full_logged_total 8054
telemt_desync_suppressed_total 15418
telemt_desync_frames_bucket_total{bucket="1_2"} 5631
telemt_desync_frames_bucket_total{bucket="3_10"} 9113
telemt_desync_frames_bucket_total{bucket="gt_10"} 8728
telemt_pool_swap_total 128
telemt_pool_force_close_total 3794
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 38391
telemt_me_writer_removed_unexpected_total 879
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3173
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36039
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3576
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34597
telemt_me_writer_teardown_success_total{mode="normal"} 39212
telemt_me_writer_teardown_noop_total 38397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77609
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.374756
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77609
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 804
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 4969234
telemt_user_connections_current{user="hello"} 2686
telemt_user_octets_from_client{user="hello"} 145673387113 (135.67 GB)
telemt_user_octets_to_client{user="hello"} 2372676540515 (2.16 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1210
telemt_user_unique_ips_recent_window{user="hello"} 326
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 117465.7 (32h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6598129
telemt_connections_bad_total 559865
telemt_connections_current 2313
telemt_connections_me_current 2313
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 219272
telemt_upstream_connect_attempt_total 54208
telemt_upstream_connect_success_total 53666
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 53809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24924
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 2407
telemt_me_reconnect_success_total 1066
telemt_me_reader_eof_total 1001
telemt_me_idle_close_by_peer_total 1001
telemt_me_route_drop_no_conn_total 2325002
telemt_me_route_drop_channel_closed_total 139
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4907402
telemt_me_endpoint_quarantine_total 837
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 875
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 23364
telemt_desync_full_logged_total 7921
telemt_desync_suppressed_total 15443
telemt_desync_frames_bucket_total{bucket="1_2"} 5688
telemt_desync_frames_bucket_total{bucket="3_10"} 8956
telemt_desync_frames_bucket_total{bucket="gt_10"} 8720
telemt_pool_swap_total 126
telemt_pool_force_close_total 3662
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 413
telemt_me_draining_writers_reap_progress_total 39485
telemt_me_writer_removed_unexpected_total 991
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3393
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37103
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3425
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 237
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35823
telemt_me_writer_teardown_success_total{mode="normal"} 40496
telemt_me_writer_teardown_noop_total 39497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79993
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 33.961438
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79993
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 413
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 932
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 4901935
telemt_user_connections_current{user="hello"} 2313
telemt_user_octets_from_client{user="hello"} 136854652979 (127.46 GB)
telemt_user_octets_to_client{user="hello"} 2240581463371 (2.04 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 982
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 117505.3 (32h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21116673
telemt_connections_bad_total 1783984
telemt_connections_current 3860
telemt_connections_me_current 3860
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 641866
telemt_upstream_connect_attempt_total 204865
telemt_upstream_connect_success_total 186524
telemt_upstream_connect_fail_total 16479
telemt_upstream_connect_attempts_per_request{bucket="1"} 203003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45385
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8953
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16479
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65269
telemt_me_reconnect_success_total 2487
telemt_me_reader_eof_total 1576
telemt_me_idle_close_by_peer_total 1575
telemt_me_route_drop_no_conn_total 39985449
telemt_me_route_drop_channel_closed_total 129
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16973699
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 911
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 921
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_me_writers_active_current 42
telemt_desync_total 32882
telemt_desync_full_logged_total 9919
telemt_desync_suppressed_total 22963
telemt_desync_frames_bucket_total{bucket="1_2"} 7171
telemt_desync_frames_bucket_total{bucket="3_10"} 14591
telemt_desync_frames_bucket_total{bucket="gt_10"} 11120
telemt_pool_swap_total 121
telemt_pool_force_close_total 3916
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 846
telemt_me_draining_writers_reap_progress_total 37062
telemt_me_writer_removed_unexpected_total 2313
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4977
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34145
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3358
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 558
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33146
telemt_me_writer_teardown_success_total{mode="normal"} 39122
telemt_me_writer_teardown_noop_total 37089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76211
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 218.212586
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76211
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 846
telemt_me_refill_failed_total 3811
telemt_me_writer_restored_same_endpoint_total 1707
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 584
telemt_user_connections_total{user="hello"} 17108263
telemt_user_connections_current{user="hello"} 3860
telemt_user_octets_from_client{user="hello"} 250667367172 (233.45 GB)
telemt_user_octets_to_client{user="hello"} 1316512219999 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1604
telemt_user_unique_ips_recent_window{user="hello"} 487
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 117472.4 (32h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6372202
telemt_connections_bad_total 609728
telemt_connections_current 2749
telemt_connections_me_current 2749
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 134646
telemt_upstream_connect_attempt_total 62750
telemt_upstream_connect_success_total 62024
telemt_upstream_connect_fail_total 620
telemt_upstream_connect_attempts_per_request{bucket="1"} 62644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 620
telemt_me_reconnect_attempts_total 69885
telemt_me_reconnect_success_total 1880
telemt_me_reader_eof_total 1653
telemt_me_idle_close_by_peer_total 1652
telemt_me_route_drop_no_conn_total 2460803
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4951779
telemt_me_endpoint_quarantine_total 796
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 893
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 24705
telemt_desync_full_logged_total 8657
telemt_desync_suppressed_total 16048
telemt_desync_frames_bucket_total{bucket="1_2"} 4873
telemt_desync_frames_bucket_total{bucket="3_10"} 9539
telemt_desync_frames_bucket_total{bucket="gt_10"} 10293
telemt_pool_swap_total 122
telemt_pool_force_close_total 3490
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 413
telemt_me_draining_writers_reap_progress_total 41547
telemt_me_writer_removed_unexpected_total 1689
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4206
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39062
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3084
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38057
telemt_me_writer_teardown_success_total{mode="normal"} 43268
telemt_me_writer_teardown_noop_total 41548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84816
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.951926
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84816
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 413
telemt_me_refill_failed_total 4213
telemt_me_writer_restored_same_endpoint_total 1570
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 4943907
telemt_user_connections_current{user="hello"} 2749
telemt_user_octets_from_client{user="hello"} 128889208376 (120.04 GB)
telemt_user_octets_to_client{user="hello"} 2051122592282 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1199
telemt_user_unique_ips_recent_window{user="hello"} 333
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 54308.4 (15h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4356103
telemt_connections_bad_total 182557
telemt_connections_current 2200
telemt_connections_me_current 2200
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1720090
telemt_upstream_connect_attempt_total 31571
telemt_upstream_connect_success_total 31360
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 31564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_reconnect_attempts_total 46077
telemt_me_reconnect_success_total 1028
telemt_me_reader_eof_total 718
telemt_me_idle_close_by_peer_total 718
telemt_me_route_drop_no_conn_total 1098335
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2155921
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 423
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 11700
telemt_desync_full_logged_total 4010
telemt_desync_suppressed_total 7690
telemt_desync_frames_bucket_total{bucket="1_2"} 2254
telemt_desync_frames_bucket_total{bucket="3_10"} 4483
telemt_desync_frames_bucket_total{bucket="gt_10"} 4963
telemt_pool_swap_total 59
telemt_pool_force_close_total 1730
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 153
telemt_me_draining_writers_reap_progress_total 20236
telemt_me_writer_removed_unexpected_total 789
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1740
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19314
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1521
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 209
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18506
telemt_me_writer_teardown_success_total{mode="normal"} 21054
telemt_me_writer_teardown_noop_total 20238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41292
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.695745
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41292
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 153
telemt_me_refill_failed_total 2617
telemt_me_writer_restored_same_endpoint_total 917
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2158458
telemt_user_connections_current{user="hello"} 2200
telemt_user_octets_from_client{user="hello"} 58006712828 (54.02 GB)
telemt_user_octets_to_client{user="hello"} 942017874650 (877.32 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 956
telemt_user_unique_ips_recent_window{user="hello"} 307
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 35279.1 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249195
telemt_connections_bad_total 1899
telemt_connections_current 462
telemt_connections_me_current 462
telemt_handshake_timeouts_total 6497
telemt_upstream_connect_attempt_total 17082
telemt_upstream_connect_success_total 17039
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 17078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9754
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 410
telemt_me_reconnect_success_total 232
telemt_me_reader_eof_total 233
telemt_me_idle_close_by_peer_total 233
telemt_me_route_drop_no_conn_total 69828
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221863
telemt_me_endpoint_quarantine_total 345
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 306
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1209
telemt_desync_full_logged_total 329
telemt_desync_suppressed_total 880
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 463
telemt_desync_frames_bucket_total{bucket="gt_10"} 322
telemt_pool_swap_total 39
telemt_pool_force_close_total 846
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 15458
telemt_me_writer_removed_unexpected_total 222
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 980
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14711
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 844
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14612
telemt_me_writer_teardown_success_total{mode="normal"} 15691
telemt_me_writer_teardown_noop_total 15458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31149
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.229539
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31149
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 201
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 221510
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 3722077944 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 136230952024 (126.87 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 117476.9 (32h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7722085
telemt_connections_bad_total 769274
telemt_connections_current 2947
telemt_connections_me_current 2947
telemt_handshake_timeouts_total 219791
telemt_upstream_connect_attempt_total 46339
telemt_upstream_connect_success_total 46169
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 46302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_reconnect_attempts_total 1685
telemt_me_reconnect_success_total 902
telemt_me_reader_eof_total 896
telemt_me_idle_close_by_peer_total 896
telemt_me_route_drop_no_conn_total 2194479
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5754862
telemt_me_endpoint_quarantine_total 841
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 903
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 22513
telemt_desync_full_logged_total 7417
telemt_desync_suppressed_total 15096
telemt_desync_frames_bucket_total{bucket="1_2"} 5642
telemt_desync_frames_bucket_total{bucket="3_10"} 8174
telemt_desync_frames_bucket_total{bucket="gt_10"} 8697
telemt_pool_swap_total 130
telemt_pool_force_close_total 3464
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 410
telemt_me_draining_writers_reap_progress_total 41836
telemt_me_writer_removed_unexpected_total 859
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3267
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39455
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3376
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38372
telemt_me_writer_teardown_success_total{mode="normal"} 42722
telemt_me_writer_teardown_noop_total 41838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84560
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.840509
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84560
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 410
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 807
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 5729471
telemt_user_connections_current{user="hello"} 2947
telemt_user_octets_from_client{user="hello"} 113466307848 (105.67 GB)
telemt_user_octets_to_client{user="hello"} 2677451564084 (2.44 TB)
telemt_user_unique_ips_current{user="hello"} 1173
telemt_user_unique_ips_recent_window{user="hello"} 333
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 117473.5 (32h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6701031
telemt_connections_bad_total 655806
telemt_connections_current 2901
telemt_connections_me_current 2901
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 181946
telemt_upstream_connect_attempt_total 62183
telemt_upstream_connect_success_total 61714
telemt_upstream_connect_fail_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 62123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 409
telemt_me_reconnect_attempts_total 5769
telemt_me_reconnect_success_total 1272
telemt_me_reader_eof_total 1142
telemt_me_idle_close_by_peer_total 1142
telemt_me_seq_mismatch_total 54
telemt_me_route_drop_no_conn_total 2248593
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5121684
telemt_me_endpoint_quarantine_total 928
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 901
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 21291
telemt_desync_full_logged_total 7088
telemt_desync_suppressed_total 14203
telemt_desync_frames_bucket_total{bucket="1_2"} 5367
telemt_desync_frames_bucket_total{bucket="3_10"} 7789
telemt_desync_frames_bucket_total{bucket="gt_10"} 8135
telemt_pool_swap_total 128
telemt_pool_force_close_total 3410
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 411
telemt_me_draining_writers_reap_progress_total 40403
telemt_me_writer_removed_unexpected_total 1154
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3822
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37792
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3187
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36993
telemt_me_writer_teardown_success_total{mode="normal"} 41614
telemt_me_writer_teardown_noop_total 40407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82021
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.605257
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82021
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 411
telemt_me_refill_failed_total 259
telemt_me_writer_restored_same_endpoint_total 995
telemt_me_writer_restored_fallback_total 72
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5124404
telemt_user_connections_current{user="hello"} 2901
telemt_user_octets_from_client{user="hello"} 96280761445 (89.67 GB)
telemt_user_octets_to_client{user="hello"} 2210747805064 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1185
telemt_user_unique_ips_recent_window{user="hello"} 376
```