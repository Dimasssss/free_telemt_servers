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

# Server Metrics 2026-03-22 08:03:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 39399.4 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 875647
telemt_connections_bad_total 53011
telemt_connections_current 1831
telemt_connections_me_current 1831
telemt_handshake_timeouts_total 41318
telemt_upstream_connect_attempt_total 15794
telemt_upstream_connect_success_total 15793
telemt_upstream_connect_attempts_per_request{bucket="1"} 15793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 436
telemt_me_reconnect_success_total 247
telemt_me_reader_eof_total 245
telemt_me_idle_close_by_peer_total 245
telemt_me_route_drop_no_conn_total 403589
telemt_me_route_drop_channel_closed_total 138
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 726673
telemt_me_endpoint_quarantine_total 279
telemt_me_single_endpoint_shadow_rotate_total 319
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 5660
telemt_desync_full_logged_total 1593
telemt_desync_suppressed_total 4067
telemt_desync_frames_bucket_total{bucket="1_2"} 1764
telemt_desync_frames_bucket_total{bucket="3_10"} 2117
telemt_desync_frames_bucket_total{bucket="gt_10"} 1779
telemt_pool_swap_total 43
telemt_pool_force_close_total 1205
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 14329
telemt_me_writer_removed_unexpected_total 242
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 993
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13531
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13124
telemt_me_writer_teardown_success_total{mode="normal"} 14524
telemt_me_writer_teardown_noop_total 14330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28854
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.346024
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28854
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 227
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 725348
telemt_user_connections_current{user="hello"} 1831
telemt_user_octets_from_client{user="hello"} 10182170536 (9.48 GB)
telemt_user_octets_to_client{user="hello"} 241979651588 (225.36 GB)
telemt_user_unique_ips_current{user="hello"} 657
telemt_user_unique_ips_recent_window{user="hello"} 368
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 52766.1 (14h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1356615
telemt_connections_bad_total 131001
telemt_connections_current 2379
telemt_connections_me_current 2379
telemt_handshake_timeouts_total 40914
telemt_upstream_connect_attempt_total 27555
telemt_upstream_connect_success_total 27143
telemt_upstream_connect_fail_total 360
telemt_upstream_connect_attempts_per_request{bucket="1"} 27503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 360
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2044
telemt_me_reconnect_success_total 873
telemt_me_reader_eof_total 762
telemt_me_idle_close_by_peer_total 762
telemt_me_route_drop_no_conn_total 548740
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1023303
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 421
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 4455
telemt_desync_full_logged_total 2610
telemt_desync_suppressed_total 1845
telemt_desync_frames_bucket_total{bucket="1_2"} 961
telemt_desync_frames_bucket_total{bucket="3_10"} 1722
telemt_desync_frames_bucket_total{bucket="gt_10"} 1772
telemt_pool_swap_total 55
telemt_pool_force_close_total 1480
telemt_me_writer_close_signal_drop_total 123
telemt_me_draining_writers_reap_progress_total 21514
telemt_me_writer_removed_unexpected_total 734
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1958
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20277
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20034
telemt_me_writer_teardown_success_total{mode="normal"} 22235
telemt_me_writer_teardown_noop_total 21514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43749
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.916774
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43749
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 123
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 675
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 1024962
telemt_user_connections_current{user="hello"} 2379
telemt_user_octets_from_client{user="hello"} 16005640578 (14.91 GB)
telemt_user_octets_to_client{user="hello"} 364151768251 (339.14 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 1382
telemt_user_unique_ips_recent_window{user="hello"} 566
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 127626.0 (35h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9368869
telemt_connections_bad_total 850631
telemt_connections_current 4845
telemt_connections_me_current 4845
telemt_handshake_timeouts_total 286779
telemt_upstream_connect_attempt_total 46994
telemt_upstream_connect_success_total 46914
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 46922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25552
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1841
telemt_me_reconnect_success_total 934
telemt_me_reader_eof_total 938
telemt_me_idle_close_by_peer_total 938
telemt_me_route_drop_no_conn_total 5104733
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7356391
telemt_me_endpoint_quarantine_total 802
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 958
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
telemt_me_writers_active_current 44
telemt_desync_total 32005
telemt_desync_full_logged_total 10560
telemt_desync_suppressed_total 21445
telemt_desync_frames_bucket_total{bucket="1_2"} 7001
telemt_desync_frames_bucket_total{bucket="3_10"} 12404
telemt_desync_frames_bucket_total{bucket="gt_10"} 12600
telemt_pool_swap_total 138
telemt_pool_force_close_total 4564
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 42908
telemt_me_writer_removed_unexpected_total 902
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3568
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39720
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4287
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 277
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38344
telemt_me_writer_teardown_success_total{mode="normal"} 43288
telemt_me_writer_teardown_noop_total 42952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86240
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 182.166518
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86240
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 832
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 7346808
telemt_user_connections_current{user="hello"} 4845
telemt_user_octets_from_client{user="hello"} 122920527880 (114.48 GB)
telemt_user_octets_to_client{user="hello"} 2488246579472 (2.26 TB)
telemt_user_unique_ips_current{user="hello"} 1903
telemt_user_unique_ips_recent_window{user="hello"} 673
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 127627.1 (35h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7700103
telemt_connections_bad_total 683841
telemt_connections_current 3660
telemt_connections_me_current 3660
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 250364
telemt_upstream_connect_attempt_total 53209
telemt_upstream_connect_success_total 52737
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 52977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2803
telemt_me_reconnect_success_total 1051
telemt_me_reader_eof_total 971
telemt_me_idle_close_by_peer_total 971
telemt_me_route_drop_no_conn_total 2582805
telemt_me_route_drop_channel_closed_total 312
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5700384
telemt_me_endpoint_quarantine_total 808
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 985
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
telemt_me_writers_active_current 43
telemt_desync_total 26125
telemt_desync_full_logged_total 8939
telemt_desync_suppressed_total 17186
telemt_desync_frames_bucket_total{bucket="1_2"} 6253
telemt_desync_frames_bucket_total{bucket="3_10"} 10119
telemt_desync_frames_bucket_total{bucket="gt_10"} 9753
telemt_pool_swap_total 139
telemt_pool_force_close_total 4140
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 438
telemt_me_draining_writers_reap_progress_total 41306
telemt_me_writer_removed_unexpected_total 995
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3506
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38715
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3895
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 245
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37166
telemt_me_writer_teardown_success_total{mode="normal"} 42221
telemt_me_writer_teardown_noop_total 41312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83533
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.667963
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83533
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 438
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 892
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 5623246
telemt_user_connections_current{user="hello"} 3660
telemt_user_octets_from_client{user="hello"} 157424478751 (146.61 GB)
telemt_user_octets_to_client{user="hello"} 2702808071094 (2.46 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1545
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 127592.5 (35h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7434271
telemt_connections_bad_total 614124
telemt_connections_current 3938
telemt_connections_me_current 3938
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 246116
telemt_upstream_connect_attempt_total 57626
telemt_upstream_connect_success_total 56956
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 57103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1298
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2739
telemt_me_reconnect_success_total 1191
telemt_me_reader_eof_total 1099
telemt_me_idle_close_by_peer_total 1099
telemt_me_route_drop_no_conn_total 2993019
telemt_me_route_drop_channel_closed_total 174
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5541947
telemt_me_endpoint_quarantine_total 897
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 942
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 25914
telemt_desync_full_logged_total 8847
telemt_desync_suppressed_total 17067
telemt_desync_frames_bucket_total{bucket="1_2"} 6266
telemt_desync_frames_bucket_total{bucket="3_10"} 9960
telemt_desync_frames_bucket_total{bucket="gt_10"} 9688
telemt_pool_swap_total 136
telemt_pool_force_close_total 4045
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 459
telemt_me_draining_writers_reap_progress_total 42350
telemt_me_writer_removed_unexpected_total 1109
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3743
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39699
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3743
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38305
telemt_me_writer_teardown_success_total{mode="normal"} 43442
telemt_me_writer_teardown_noop_total 42362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85804
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 44.371852
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85804
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 459
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1032
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 5535158
telemt_user_connections_current{user="hello"} 3938
telemt_user_octets_from_client{user="hello"} 145430024855 (135.44 GB)
telemt_user_octets_to_client{user="hello"} 2464549884583 (2.24 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1664
telemt_user_unique_ips_recent_window{user="hello"} 566
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 127630.5 (35h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23835385
telemt_connections_bad_total 1964452
telemt_connections_current 6045
telemt_connections_me_current 6045
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 691904
telemt_upstream_connect_attempt_total 241236
telemt_upstream_connect_success_total 221485
telemt_upstream_connect_fail_total 17758
telemt_upstream_connect_attempts_per_request{bucket="1"} 239243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52401
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17758
telemt_me_keepalive_timeout_total 423
telemt_me_reconnect_attempts_total 66515
telemt_me_reconnect_success_total 2694
telemt_me_reader_eof_total 1674
telemt_me_idle_close_by_peer_total 1672
telemt_me_route_drop_no_conn_total 45999154
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19252450
telemt_me_writer_pick_total{mode="p2c",result="full"} 227
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_writer_pick_blocking_fallback_total 222
telemt_me_endpoint_quarantine_total 991
telemt_me_single_endpoint_outage_enter_total 164
telemt_me_single_endpoint_outage_exit_total 164
telemt_me_single_endpoint_outage_reconnect_attempt_total 335
telemt_me_single_endpoint_outage_reconnect_success_total 86
telemt_me_single_endpoint_quarantine_bypass_total 335
telemt_me_single_endpoint_shadow_rotate_total 1003
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 71
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
telemt_desync_total 37318
telemt_desync_full_logged_total 11057
telemt_desync_suppressed_total 26261
telemt_desync_frames_bucket_total{bucket="1_2"} 8286
telemt_desync_frames_bucket_total{bucket="3_10"} 16488
telemt_desync_frames_bucket_total{bucket="gt_10"} 12544
telemt_pool_swap_total 132
telemt_pool_force_close_total 4184
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 965
telemt_me_draining_writers_reap_progress_total 39761
telemt_me_writer_removed_unexpected_total 2497
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5378
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36611
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3595
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 589
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35577
telemt_me_writer_teardown_success_total{mode="normal"} 41989
telemt_me_writer_teardown_noop_total 39793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81782
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 284.036713
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81782
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 965
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1822
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14757
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 19418070
telemt_user_connections_current{user="hello"} 6045
telemt_user_octets_from_client{user="hello"} 276759574291 (257.75 GB)
telemt_user_octets_to_client{user="hello"} 1430115687543 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 503035
telemt_user_msgs_to_client{user="hello"} 1007896
telemt_user_unique_ips_current{user="hello"} 2124
telemt_user_unique_ips_recent_window{user="hello"} 1253
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 127598.1 (35h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7060972
telemt_connections_bad_total 642062
telemt_connections_current 3889
telemt_connections_me_current 3889
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 145515
telemt_upstream_connect_attempt_total 66062
telemt_upstream_connect_success_total 65294
telemt_upstream_connect_fail_total 662
telemt_upstream_connect_attempts_per_request{bucket="1"} 65956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27633
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 662
telemt_me_reconnect_attempts_total 70198
telemt_me_reconnect_success_total 1960
telemt_me_reader_eof_total 1727
telemt_me_idle_close_by_peer_total 1726
telemt_me_route_drop_no_conn_total 2711322
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5538640
telemt_me_endpoint_quarantine_total 853
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 969
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
telemt_me_writers_active_current 46
telemt_desync_total 27899
telemt_desync_full_logged_total 9730
telemt_desync_suppressed_total 18169
telemt_desync_frames_bucket_total{bucket="1_2"} 5581
telemt_desync_frames_bucket_total{bucket="3_10"} 10720
telemt_desync_frames_bucket_total{bucket="gt_10"} 11598
telemt_pool_swap_total 133
telemt_pool_force_close_total 3832
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 449
telemt_me_draining_writers_reap_progress_total 44509
telemt_me_writer_removed_unexpected_total 1758
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4459
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41833
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 426
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40677
telemt_me_writer_teardown_success_total{mode="normal"} 46292
telemt_me_writer_teardown_noop_total 44510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90802
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.157890
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90802
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 449
telemt_me_refill_failed_total 4224
telemt_me_writer_restored_same_endpoint_total 1632
telemt_me_writer_restored_fallback_total 39
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7319
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5529523
telemt_user_connections_current{user="hello"} 3889
telemt_user_octets_from_client{user="hello"} 139874010352 (130.27 GB)
telemt_user_octets_to_client{user="hello"} 2309509397822 (2.10 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1563
telemt_user_unique_ips_recent_window{user="hello"} 623
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 64434.2 (17h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5416710
telemt_connections_bad_total 215757
telemt_connections_current 4318
telemt_connections_me_current 4318
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2155019
telemt_upstream_connect_attempt_total 35056
telemt_upstream_connect_success_total 34810
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 35049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_reconnect_attempts_total 46364
telemt_me_reconnect_success_total 1136
telemt_me_reader_eof_total 828
telemt_me_idle_close_by_peer_total 828
telemt_me_route_drop_no_conn_total 1324254
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2703466
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 495
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
telemt_me_writers_active_current 87
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 14556
telemt_desync_full_logged_total 4993
telemt_desync_suppressed_total 9563
telemt_desync_frames_bucket_total{bucket="1_2"} 2852
telemt_desync_frames_bucket_total{bucket="3_10"} 5594
telemt_desync_frames_bucket_total{bucket="gt_10"} 6110
telemt_pool_swap_total 69
telemt_pool_force_close_total 2031
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 188
telemt_me_draining_writers_reap_progress_total 23249
telemt_me_writer_removed_unexpected_total 898
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1994
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22175
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 231
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21218
telemt_me_writer_teardown_success_total{mode="normal"} 24169
telemt_me_writer_teardown_noop_total 23251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47420
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.284015
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47420
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 188
telemt_me_refill_failed_total 2627
telemt_me_writer_restored_same_endpoint_total 1015
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2704990
telemt_user_connections_current{user="hello"} 4318
telemt_user_octets_from_client{user="hello"} 68769734852 (64.05 GB)
telemt_user_octets_to_client{user="hello"} 1198666089998 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1815
telemt_user_unique_ips_recent_window{user="hello"} 564
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 45404.8 (12h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 374231
telemt_connections_bad_total 2524
telemt_connections_current 1021
telemt_connections_me_current 1021
telemt_handshake_timeouts_total 7968
telemt_upstream_connect_attempt_total 21529
telemt_upstream_connect_success_total 21475
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 21525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 927
telemt_me_reconnect_success_total 313
telemt_me_reader_eof_total 312
telemt_me_idle_close_by_peer_total 312
telemt_me_route_drop_no_conn_total 116093
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340096
telemt_me_endpoint_quarantine_total 433
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 393
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 1565
telemt_desync_full_logged_total 450
telemt_desync_suppressed_total 1115
telemt_desync_frames_bucket_total{bucket="1_2"} 488
telemt_desync_frames_bucket_total{bucket="3_10"} 604
telemt_desync_frames_bucket_total{bucket="gt_10"} 473
telemt_pool_swap_total 50
telemt_pool_force_close_total 1141
telemt_me_writer_close_signal_drop_total 42
telemt_me_draining_writers_reap_progress_total 19459
telemt_me_writer_removed_unexpected_total 298
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1293
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18478
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18318
telemt_me_writer_teardown_success_total{mode="normal"} 19771
telemt_me_writer_teardown_noop_total 19459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39230
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.807274
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39230
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 42
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 267
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 339514
telemt_user_connections_current{user="hello"} 1021
telemt_user_octets_from_client{user="hello"} 6106929336 (5.69 GB)
telemt_user_octets_to_client{user="hello"} 181612834120 (169.14 GB)
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 127602.3 (35h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8669064
telemt_connections_bad_total 963498
telemt_connections_current 4778
telemt_connections_me_current 4778
telemt_handshake_timeouts_total 243030
telemt_upstream_connect_attempt_total 49798
telemt_upstream_connect_success_total 49617
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 49759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25012
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_reconnect_attempts_total 1838
telemt_me_reconnect_success_total 1000
telemt_me_reader_eof_total 978
telemt_me_idle_close_by_peer_total 978
telemt_me_route_drop_no_conn_total 2423116
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 24
telemt_me_route_drop_queue_full_profile_total{profile="high"} 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6432957
telemt_me_endpoint_quarantine_total 900
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 971
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
telemt_me_writers_active_current 44
telemt_desync_total 25796
telemt_desync_full_logged_total 8478
telemt_desync_suppressed_total 17318
telemt_desync_frames_bucket_total{bucket="1_2"} 6368
telemt_desync_frames_bucket_total{bucket="3_10"} 9374
telemt_desync_frames_bucket_total{bucket="gt_10"} 10054
telemt_pool_swap_total 141
telemt_pool_force_close_total 3779
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 451
telemt_me_draining_writers_reap_progress_total 44950
telemt_me_writer_removed_unexpected_total 939
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3560
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42358
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3683
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 96
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41171
telemt_me_writer_teardown_success_total{mode="normal"} 45918
telemt_me_writer_teardown_noop_total 44952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90870
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.558304
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90870
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 451
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 884
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6406344
telemt_user_connections_current{user="hello"} 4778
telemt_user_octets_from_client{user="hello"} 125897953036 (117.25 GB)
telemt_user_octets_to_client{user="hello"} 3007467994260 (2.74 TB)
telemt_user_unique_ips_current{user="hello"} 1810
telemt_user_unique_ips_recent_window{user="hello"} 640
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 127599.2 (35h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7566486
telemt_connections_bad_total 828229
telemt_connections_current 4422
telemt_connections_me_current 4422
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 202521
telemt_upstream_connect_attempt_total 65863
telemt_upstream_connect_success_total 65357
telemt_upstream_connect_fail_total 443
telemt_upstream_connect_attempts_per_request{bucket="1"} 65800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26732
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 625
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 443
telemt_me_reconnect_attempts_total 6159
telemt_me_reconnect_success_total 1413
telemt_me_reader_eof_total 1274
telemt_me_idle_close_by_peer_total 1274
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2534209
telemt_me_route_drop_channel_closed_total 208
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5755320
telemt_me_endpoint_quarantine_total 997
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 970
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
telemt_desync_total 24608
telemt_desync_full_logged_total 8186
telemt_desync_suppressed_total 16422
telemt_desync_frames_bucket_total{bucket="1_2"} 6072
telemt_desync_frames_bucket_total{bucket="3_10"} 9049
telemt_desync_frames_bucket_total{bucket="gt_10"} 9487
telemt_pool_swap_total 138
telemt_pool_force_close_total 3722
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 452
telemt_me_draining_writers_reap_progress_total 43634
telemt_me_writer_removed_unexpected_total 1288
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4155
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40829
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 260
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39912
telemt_me_writer_teardown_success_total{mode="normal"} 44984
telemt_me_writer_teardown_noop_total 43638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88622
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.707672
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88622
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 452
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 1108
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 102
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 5756690
telemt_user_connections_current{user="hello"} 4422
telemt_user_octets_from_client{user="hello"} 105987264757 (98.71 GB)
telemt_user_octets_to_client{user="hello"} 2500036212852 (2.27 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1752
telemt_user_unique_ips_recent_window{user="hello"} 659
```