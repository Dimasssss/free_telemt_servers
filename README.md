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

# Server Metrics 2026-03-22 11:47:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 52870.7 (14h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1525861
telemt_connections_bad_total 73650
telemt_connections_current 1741
telemt_connections_me_current 1741
telemt_handshake_timeouts_total 69717
telemt_upstream_connect_attempt_total 20242
telemt_upstream_connect_success_total 20241
telemt_upstream_connect_attempts_per_request{bucket="1"} 20241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 50
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 752
telemt_me_reconnect_success_total 337
telemt_me_reader_eof_total 334
telemt_me_idle_close_by_peer_total 334
telemt_me_route_drop_no_conn_total 987930
telemt_me_route_drop_channel_closed_total 456
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1286979
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 376
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 425
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 7898
telemt_desync_full_logged_total 2358
telemt_desync_suppressed_total 5540
telemt_desync_frames_bucket_total{bucket="1_2"} 2260
telemt_desync_frames_bucket_total{bucket="3_10"} 2960
telemt_desync_frames_bucket_total{bucket="gt_10"} 2678
telemt_pool_swap_total 58
telemt_pool_force_close_total 1731
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 266
telemt_me_draining_writers_reap_progress_total 18448
telemt_me_writer_removed_unexpected_total 329
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1297
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17358
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1696
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16717
telemt_me_writer_teardown_success_total{mode="normal"} 18655
telemt_me_writer_teardown_noop_total 18450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37105
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 127.524323
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37105
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 266
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 300
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1284465
telemt_user_connections_current{user="hello"} 1741
telemt_user_octets_from_client{user="hello"} 20549662104 (19.14 GB)
telemt_user_octets_to_client{user="hello"} 389337186340 (362.60 GB)
telemt_user_unique_ips_current{user="hello"} 652
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 66237.0 (18h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2495967
telemt_connections_bad_total 216937
telemt_connections_current 1635
telemt_connections_me_current 1635
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 57014
telemt_upstream_connect_attempt_total 44203
telemt_upstream_connect_success_total 43688
telemt_upstream_connect_fail_total 455
telemt_upstream_connect_attempts_per_request{bucket="1"} 44143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16842
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 455
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3399
telemt_me_reconnect_success_total 1510
telemt_me_reader_eof_total 1393
telemt_me_idle_close_by_peer_total 1393
telemt_me_route_drop_no_conn_total 2160698
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1963417
telemt_me_endpoint_quarantine_total 570
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 521
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 7750
telemt_desync_full_logged_total 4381
telemt_desync_suppressed_total 3369
telemt_desync_frames_bucket_total{bucket="1_2"} 1789
telemt_desync_frames_bucket_total{bucket="3_10"} 3026
telemt_desync_frames_bucket_total{bucket="gt_10"} 2935
telemt_pool_swap_total 66
telemt_pool_force_close_total 1865
telemt_me_writer_close_signal_drop_total 155
telemt_me_draining_writers_reap_progress_total 26456
telemt_me_writer_removed_unexpected_total 1355
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2914
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24895
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1655
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24591
telemt_me_writer_teardown_success_total{mode="normal"} 27809
telemt_me_writer_teardown_noop_total 26456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54265
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.112658
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54265
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 155
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1255
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1975244
telemt_user_connections_current{user="hello"} 1635
telemt_user_octets_from_client{user="hello"} 24735542427 (23.04 GB)
telemt_user_octets_to_client{user="hello"} 490544777726 (456.86 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 967
telemt_user_unique_ips_recent_window{user="hello"} 618
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 141097.0 (39h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12451116
telemt_connections_bad_total 1077063
telemt_connections_current 5084
telemt_connections_me_current 5084
telemt_handshake_timeouts_total 325154
telemt_upstream_connect_attempt_total 51282
telemt_upstream_connect_success_total 51202
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 51210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2213
telemt_me_reconnect_success_total 1140
telemt_me_reader_eof_total 1110
telemt_me_idle_close_by_peer_total 1109
telemt_me_route_drop_no_conn_total 10090875
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9950209
telemt_me_endpoint_quarantine_total 893
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1052
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_active_current 51
telemt_desync_total 40864
telemt_desync_full_logged_total 13089
telemt_desync_suppressed_total 27775
telemt_desync_frames_bucket_total{bucket="1_2"} 9201
telemt_desync_frames_bucket_total{bucket="3_10"} 15977
telemt_desync_frames_bucket_total{bucket="gt_10"} 15686
telemt_pool_swap_total 152
telemt_pool_force_close_total 5130
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 803
telemt_me_draining_writers_reap_progress_total 46765
telemt_me_writer_removed_unexpected_total 1070
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4017
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43213
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4787
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 343
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41635
telemt_me_writer_teardown_success_total{mode="normal"} 47230
telemt_me_writer_teardown_noop_total 46809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94039
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 218.560018
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94039
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 803
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 991
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 9939121
telemt_user_connections_current{user="hello"} 5084
telemt_user_octets_from_client{user="hello"} 147323710356 (137.21 GB)
telemt_user_octets_to_client{user="hello"} 2795184249616 (2.54 TB)
telemt_user_unique_ips_current{user="hello"} 2030
telemt_user_unique_ips_recent_window{user="hello"} 821
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 141098.4 (39h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9359509
telemt_connections_bad_total 846518
telemt_connections_current 4403
telemt_connections_me_current 4403
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 284727
telemt_upstream_connect_attempt_total 57818
telemt_upstream_connect_success_total 57237
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 57504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3262
telemt_me_reconnect_success_total 1326
telemt_me_reader_eof_total 1212
telemt_me_idle_close_by_peer_total 1212
telemt_me_route_drop_no_conn_total 3785411
telemt_me_route_drop_channel_closed_total 386
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6983053
telemt_me_endpoint_quarantine_total 888
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1077
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 31687
telemt_desync_full_logged_total 10705
telemt_desync_suppressed_total 20982
telemt_desync_frames_bucket_total{bucket="1_2"} 7807
telemt_desync_frames_bucket_total{bucket="3_10"} 12192
telemt_desync_frames_bucket_total{bucket="gt_10"} 11688
telemt_pool_swap_total 151
telemt_pool_force_close_total 4633
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 541
telemt_me_draining_writers_reap_progress_total 45252
telemt_me_writer_removed_unexpected_total 1245
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4007
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42384
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40619
telemt_me_writer_teardown_success_total{mode="normal"} 46391
telemt_me_writer_teardown_noop_total 45260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91651
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 71.516823
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91651
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 541
telemt_me_refill_failed_total 105
telemt_me_writer_restored_same_endpoint_total 1134
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 6904279
telemt_user_connections_current{user="hello"} 4403
telemt_user_octets_from_client{user="hello"} 180826880131 (168.41 GB)
telemt_user_octets_to_client{user="hello"} 3174951916894 (2.89 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1702
telemt_user_unique_ips_recent_window{user="hello"} 634
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 141064.1 (39h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8868127
telemt_connections_bad_total 742629
telemt_connections_current 4462
telemt_connections_me_current 4462
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 282306
telemt_upstream_connect_attempt_total 62137
telemt_upstream_connect_success_total 61413
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 61560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1407
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3773
telemt_me_reconnect_success_total 1586
telemt_me_reader_eof_total 1471
telemt_me_idle_close_by_peer_total 1471
telemt_me_route_drop_no_conn_total 3767794
telemt_me_route_drop_channel_closed_total 258
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6670340
telemt_me_endpoint_quarantine_total 961
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1030
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_me_writers_active_current 87
telemt_desync_total 31011
telemt_desync_full_logged_total 10459
telemt_desync_suppressed_total 20552
telemt_desync_frames_bucket_total{bucket="1_2"} 7666
telemt_desync_frames_bucket_total{bucket="3_10"} 11936
telemt_desync_frames_bucket_total{bucket="gt_10"} 11409
telemt_pool_swap_total 147
telemt_pool_force_close_total 4522
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 539
telemt_me_draining_writers_reap_progress_total 45973
telemt_me_writer_removed_unexpected_total 1502
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4396
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43017
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4087
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 435
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41451
telemt_me_writer_teardown_success_total{mode="normal"} 47413
telemt_me_writer_teardown_noop_total 45990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93403
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 57.176482
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93403
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 539
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1405
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 6661536
telemt_user_connections_current{user="hello"} 4462
telemt_user_octets_from_client{user="hello"} 163438445483 (152.21 GB)
telemt_user_octets_to_client{user="hello"} 2884726813547 (2.62 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1843
telemt_user_unique_ips_recent_window{user="hello"} 600
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 11342.4 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4821918
telemt_connections_bad_total 297868
telemt_connections_current 6469
telemt_connections_me_current 6469
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 75910
telemt_upstream_connect_attempt_total 23347
telemt_upstream_connect_success_total 22300
telemt_upstream_connect_fail_total 832
telemt_upstream_connect_attempts_per_request{bucket="1"} 23132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4510
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4621
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 832
telemt_me_keepalive_timeout_total 470
telemt_me_reconnect_attempts_total 2270
telemt_me_reconnect_success_total 337
telemt_me_reader_eof_total 208
telemt_me_idle_close_by_peer_total 208
telemt_me_route_drop_no_conn_total 11223274
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4031288
telemt_me_endpoint_quarantine_total 78
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 95
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
telemt_me_writers_active_current 45
telemt_desync_total 5883
telemt_desync_full_logged_total 1529
telemt_desync_suppressed_total 4354
telemt_desync_frames_bucket_total{bucket="1_2"} 1108
telemt_desync_frames_bucket_total{bucket="3_10"} 2359
telemt_desync_frames_bucket_total{bucket="gt_10"} 2416
telemt_pool_swap_total 10
telemt_pool_force_close_total 435
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 180
telemt_me_draining_writers_reap_progress_total 2961
telemt_me_writer_removed_unexpected_total 297
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 544
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2677
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 301
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 134
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2526
telemt_me_writer_teardown_success_total{mode="normal"} 3221
telemt_me_writer_teardown_noop_total 2964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6185
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.457544
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6185
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 180
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 4046512
telemt_user_connections_current{user="hello"} 6469
telemt_user_octets_from_client{user="hello"} 21708569942 (20.22 GB)
telemt_user_octets_to_client{user="hello"} 117478289355 (109.41 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2442
telemt_user_unique_ips_recent_window{user="hello"} 1310
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 141069.1 (39h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8620534
telemt_connections_bad_total 741160
telemt_connections_current 4771
telemt_connections_me_current 4771
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 180799
telemt_upstream_connect_attempt_total 87280
telemt_upstream_connect_success_total 86414
telemt_upstream_connect_fail_total 745
telemt_upstream_connect_attempts_per_request{bucket="1"} 87159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30967
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 745
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70713
telemt_me_reconnect_success_total 2214
telemt_me_reader_eof_total 1944
telemt_me_idle_close_by_peer_total 1943
telemt_me_route_drop_no_conn_total 3895570
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6810054
telemt_me_endpoint_quarantine_total 945
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1058
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_me_writers_active_current 47
telemt_desync_total 34757
telemt_desync_full_logged_total 11970
telemt_desync_suppressed_total 22787
telemt_desync_frames_bucket_total{bucket="1_2"} 7111
telemt_desync_frames_bucket_total{bucket="3_10"} 13333
telemt_desync_frames_bucket_total{bucket="gt_10"} 14313
telemt_pool_swap_total 146
telemt_pool_force_close_total 4253
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 515
telemt_me_draining_writers_reap_progress_total 48327
telemt_me_writer_removed_unexpected_total 1973
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4985
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45340
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44074
telemt_me_writer_teardown_success_total{mode="normal"} 50325
telemt_me_writer_teardown_noop_total 48328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98653
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.843481
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98653
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 515
telemt_me_refill_failed_total 4235
telemt_me_writer_restored_same_endpoint_total 1837
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 6812882
telemt_user_connections_current{user="hello"} 4771
telemt_user_octets_from_client{user="hello"} 162513632863 (151.35 GB)
telemt_user_octets_to_client{user="hello"} 2661412993325 (2.42 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1949
telemt_user_unique_ips_recent_window{user="hello"} 629
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 77905.5 (21h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7922098
telemt_connections_bad_total 287091
telemt_connections_current 4286
telemt_connections_me_current 4286
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3288960
telemt_upstream_connect_attempt_total 39767
telemt_upstream_connect_success_total 39480
telemt_upstream_connect_fail_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 39760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 280
telemt_me_reconnect_attempts_total 47793
telemt_me_reconnect_success_total 1348
telemt_me_reader_eof_total 1016
telemt_me_idle_close_by_peer_total 1016
telemt_me_route_drop_no_conn_total 2562841
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3882749
telemt_me_endpoint_quarantine_total 527
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 592
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 21291
telemt_desync_full_logged_total 7132
telemt_desync_suppressed_total 14159
telemt_desync_frames_bucket_total{bucket="1_2"} 4369
telemt_desync_frames_bucket_total{bucket="3_10"} 8234
telemt_desync_frames_bucket_total{bucket="gt_10"} 8688
telemt_pool_swap_total 82
telemt_pool_force_close_total 2520
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 252
telemt_me_draining_writers_reap_progress_total 27416
telemt_me_writer_removed_unexpected_total 1083
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2444
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26081
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2157
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 363
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24896
telemt_me_writer_teardown_success_total{mode="normal"} 28525
telemt_me_writer_teardown_noop_total 27423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55948
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.681203
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55948
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 252
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1200
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3880326
telemt_user_connections_current{user="hello"} 4286
telemt_user_octets_from_client{user="hello"} 89502492940 (83.36 GB)
telemt_user_octets_to_client{user="hello"} 1553173932738 (1.41 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1632
telemt_user_unique_ips_recent_window{user="hello"} 593
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 58876.2 (16h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 636348
telemt_connections_bad_total 6301
telemt_connections_current 955
telemt_connections_me_current 955
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 12269
telemt_upstream_connect_attempt_total 30520
telemt_upstream_connect_success_total 30447
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 30511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 1355
telemt_me_reconnect_success_total 573
telemt_me_reader_eof_total 558
telemt_me_idle_close_by_peer_total 558
telemt_me_route_drop_no_conn_total 211552
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 574347
telemt_me_endpoint_quarantine_total 538
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 497
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_me_writers_active_current 47
telemt_desync_total 3189
telemt_desync_full_logged_total 921
telemt_desync_suppressed_total 2268
telemt_desync_frames_bucket_total{bucket="1_2"} 819
telemt_desync_frames_bucket_total{bucket="3_10"} 1252
telemt_desync_frames_bucket_total{bucket="gt_10"} 1118
telemt_pool_swap_total 62
telemt_pool_force_close_total 1517
telemt_me_writer_close_signal_drop_total 80
telemt_me_draining_writers_reap_progress_total 24898
telemt_me_writer_removed_unexpected_total 540
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1874
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23583
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1441
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23381
telemt_me_writer_teardown_success_total{mode="normal"} 25457
telemt_me_writer_teardown_noop_total 24898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50355
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.700928
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50355
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 80
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 501
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 576214
telemt_user_connections_current{user="hello"} 955
telemt_user_octets_from_client{user="hello"} 10924485817 (10.17 GB)
telemt_user_octets_to_client{user="hello"} 269147596083 (250.66 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 141073.6 (39h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10436549
telemt_connections_bad_total 1222563
telemt_connections_current 5774
telemt_connections_me_current 5774
telemt_handshake_timeouts_total 275971
telemt_upstream_connect_attempt_total 53780
telemt_upstream_connect_success_total 53575
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 53733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27094
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_reconnect_attempts_total 2096
telemt_me_reconnect_success_total 1108
telemt_me_reader_eof_total 1076
telemt_me_idle_close_by_peer_total 1076
telemt_me_route_drop_no_conn_total 3051473
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 30
telemt_me_route_drop_queue_full_profile_total{profile="high"} 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7800778
telemt_me_endpoint_quarantine_total 980
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1061
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 31911
telemt_desync_full_logged_total 10488
telemt_desync_suppressed_total 21423
telemt_desync_frames_bucket_total{bucket="1_2"} 7727
telemt_desync_frames_bucket_total{bucket="3_10"} 11732
telemt_desync_frames_bucket_total{bucket="gt_10"} 12452
telemt_pool_swap_total 156
telemt_pool_force_close_total 4250
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 521
telemt_me_draining_writers_reap_progress_total 48496
telemt_me_writer_removed_unexpected_total 1032
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3936
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45627
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4116
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 134
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44246
telemt_me_writer_teardown_success_total{mode="normal"} 49563
telemt_me_writer_teardown_noop_total 48498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98061
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.020675
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98061
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 521
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 967
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 7772181
telemt_user_connections_current{user="hello"} 5774
telemt_user_octets_from_client{user="hello"} 151012469660 (140.64 GB)
telemt_user_octets_to_client{user="hello"} 3599155674032 (3.27 TB)
telemt_user_unique_ips_current{user="hello"} 2171
telemt_user_unique_ips_recent_window{user="hello"} 748
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 141070.2 (39h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9137032
telemt_connections_bad_total 1033170
telemt_connections_current 4328
telemt_connections_me_current 4328
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 235104
telemt_upstream_connect_attempt_total 78338
telemt_upstream_connect_success_total 77777
telemt_upstream_connect_fail_total 490
telemt_upstream_connect_attempts_per_request{bucket="1"} 78267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1971
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 490
telemt_me_reconnect_attempts_total 6657
telemt_me_reconnect_success_total 1590
telemt_me_reader_eof_total 1412
telemt_me_idle_close_by_peer_total 1412
telemt_me_seq_mismatch_total 67
telemt_me_route_drop_no_conn_total 3556579
telemt_me_route_drop_channel_closed_total 282
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7004763
telemt_me_endpoint_quarantine_total 1094
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1069
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 47
telemt_desync_total 31230
telemt_desync_full_logged_total 10239
telemt_desync_suppressed_total 20991
telemt_desync_frames_bucket_total{bucket="1_2"} 7700
telemt_desync_frames_bucket_total{bucket="3_10"} 11593
telemt_desync_frames_bucket_total{bucket="gt_10"} 11937
telemt_pool_swap_total 153
telemt_pool_force_close_total 4179
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 521
telemt_me_draining_writers_reap_progress_total 47186
telemt_me_writer_removed_unexpected_total 1430
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4598
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44083
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43007
telemt_me_writer_teardown_success_total{mode="normal"} 48681
telemt_me_writer_teardown_noop_total 47190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95871
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.090688
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95871
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 521
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1240
telemt_me_writer_restored_fallback_total 91
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 7012488
telemt_user_connections_current{user="hello"} 4328
telemt_user_octets_from_client{user="hello"} 125556279489 (116.93 GB)
telemt_user_octets_to_client{user="hello"} 2871139850611 (2.61 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1737
telemt_user_unique_ips_recent_window{user="hello"} 631
```