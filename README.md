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

# Server Metrics 2026-03-22 05:29:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 30196.7 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521491
telemt_connections_bad_total 35225
telemt_connections_current 1206
telemt_connections_me_current 1206
telemt_handshake_timeouts_total 27732
telemt_upstream_connect_attempt_total 12489
telemt_upstream_connect_success_total 12488
telemt_upstream_connect_attempts_per_request{bucket="1"} 12488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8082
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 326
telemt_me_reconnect_success_total 194
telemt_me_reader_eof_total 190
telemt_me_idle_close_by_peer_total 190
telemt_me_route_drop_no_conn_total 111489
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 430803
telemt_me_endpoint_quarantine_total 233
telemt_me_single_endpoint_shadow_rotate_total 252
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
telemt_me_writers_active_current 43
telemt_desync_total 3830
telemt_desync_full_logged_total 1048
telemt_desync_suppressed_total 2782
telemt_desync_frames_bucket_total{bucket="1_2"} 1286
telemt_desync_frames_bucket_total{bucket="3_10"} 1450
telemt_desync_frames_bucket_total{bucket="gt_10"} 1094
telemt_pool_swap_total 33
telemt_pool_force_close_total 874
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 11300
telemt_me_writer_removed_unexpected_total 187
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 779
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10699
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10426
telemt_me_writer_teardown_success_total{mode="normal"} 11478
telemt_me_writer_teardown_noop_total 11301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22779
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.734659
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22779
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 176
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 429828
telemt_user_connections_current{user="hello"} 1206
telemt_user_octets_from_client{user="hello"} 5792040932 (5.39 GB)
telemt_user_octets_to_client{user="hello"} 152154949072 (141.71 GB)
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 43563.1 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 976373
telemt_connections_bad_total 76228
telemt_connections_current 787
telemt_connections_me_current 787
telemt_handshake_timeouts_total 33289
telemt_upstream_connect_attempt_total 23233
telemt_upstream_connect_success_total 22911
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 23202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_reconnect_attempts_total 1750
telemt_me_reconnect_success_total 631
telemt_me_reader_eof_total 552
telemt_me_idle_close_by_peer_total 552
telemt_me_route_drop_no_conn_total 375117
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 758855
telemt_me_endpoint_quarantine_total 410
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 356
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
telemt_me_writers_active_current 45
telemt_desync_total 3270
telemt_desync_full_logged_total 1889
telemt_desync_suppressed_total 1381
telemt_desync_frames_bucket_total{bucket="1_2"} 683
telemt_desync_frames_bucket_total{bucket="3_10"} 1254
telemt_desync_frames_bucket_total{bucket="gt_10"} 1333
telemt_pool_swap_total 47
telemt_pool_force_close_total 1233
telemt_me_writer_close_signal_drop_total 92
telemt_me_draining_writers_reap_progress_total 18020
telemt_me_writer_removed_unexpected_total 527
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1542
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17017
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16787
telemt_me_writer_teardown_success_total{mode="normal"} 18559
telemt_me_writer_teardown_noop_total 18020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36579
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.134692
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36579
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 92
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 471
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 760566
telemt_user_connections_current{user="hello"} 787
telemt_user_octets_from_client{user="hello"} 12121295167 (11.29 GB)
telemt_user_octets_to_client{user="hello"} 279230808546 (260.05 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 526
telemt_user_unique_ips_recent_window{user="hello"} 289
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 118422.9 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8262259
telemt_connections_bad_total 713702
telemt_connections_current 3012
telemt_connections_me_current 3012
telemt_handshake_timeouts_total 269106
telemt_upstream_connect_attempt_total 44131
telemt_upstream_connect_success_total 44053
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 44061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1648
telemt_me_reconnect_success_total 864
telemt_me_reader_eof_total 872
telemt_me_idle_close_by_peer_total 872
telemt_me_route_drop_no_conn_total 4634793
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6626274
telemt_me_endpoint_quarantine_total 754
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 892
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
telemt_me_writers_active_current 46
telemt_desync_total 27984
telemt_desync_full_logged_total 9318
telemt_desync_suppressed_total 18666
telemt_desync_frames_bucket_total{bucket="1_2"} 6045
telemt_desync_frames_bucket_total{bucket="3_10"} 10945
telemt_desync_frames_bucket_total{bucket="gt_10"} 10994
telemt_pool_swap_total 128
telemt_pool_force_close_total 4206
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 640
telemt_me_draining_writers_reap_progress_total 40278
telemt_me_writer_removed_unexpected_total 840
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3329
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37318
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3961
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 245
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36072
telemt_me_writer_teardown_success_total{mode="normal"} 40647
telemt_me_writer_teardown_noop_total 40322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80969
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 167.337472
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80969
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 640
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 771
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6617625
telemt_user_connections_current{user="hello"} 3012
telemt_user_octets_from_client{user="hello"} 112281129136 (104.57 GB)
telemt_user_octets_to_client{user="hello"} 2245777970560 (2.04 TB)
telemt_user_unique_ips_current{user="hello"} 1299
telemt_user_unique_ips_recent_window{user="hello"} 415
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 118424.3 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6801139
telemt_connections_bad_total 601747
telemt_connections_current 2643
telemt_connections_me_current 2643
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 227010
telemt_upstream_connect_attempt_total 48055
telemt_upstream_connect_success_total 47655
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 47858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23525
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2052
telemt_me_reconnect_success_total 927
telemt_me_reader_eof_total 905
telemt_me_idle_close_by_peer_total 905
telemt_me_route_drop_no_conn_total 2337164
telemt_me_route_drop_channel_closed_total 286
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5087038
telemt_me_endpoint_quarantine_total 750
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 914
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
telemt_desync_total 23635
telemt_desync_full_logged_total 8100
telemt_desync_suppressed_total 15535
telemt_desync_frames_bucket_total{bucket="1_2"} 5673
telemt_desync_frames_bucket_total{bucket="3_10"} 9172
telemt_desync_frames_bucket_total{bucket="gt_10"} 8790
telemt_pool_swap_total 129
telemt_pool_force_close_total 3825
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 391
telemt_me_draining_writers_reap_progress_total 38683
telemt_me_writer_removed_unexpected_total 884
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3197
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36313
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34858
telemt_me_writer_teardown_success_total{mode="normal"} 39510
telemt_me_writer_teardown_noop_total 38689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78199
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.678167
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78199
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 391
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 809
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 5008529
telemt_user_connections_current{user="hello"} 2643
telemt_user_octets_from_client{user="hello"} 146354507633 (136.30 GB)
telemt_user_octets_to_client{user="hello"} 2394776691203 (2.18 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1152
telemt_user_unique_ips_recent_window{user="hello"} 344
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 118389.1 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6643040
telemt_connections_bad_total 561061
telemt_connections_current 2559
telemt_connections_me_current 2559
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 221664
telemt_upstream_connect_attempt_total 54515
telemt_upstream_connect_success_total 53969
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 54112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25080
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 2443
telemt_me_reconnect_success_total 1069
telemt_me_reader_eof_total 1006
telemt_me_idle_close_by_peer_total 1006
telemt_me_route_drop_no_conn_total 2340318
telemt_me_route_drop_channel_closed_total 142
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4944396
telemt_me_endpoint_quarantine_total 845
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 881
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 23512
telemt_desync_full_logged_total 7979
telemt_desync_suppressed_total 15533
telemt_desync_frames_bucket_total{bucket="1_2"} 5715
telemt_desync_frames_bucket_total{bucket="3_10"} 9008
telemt_desync_frames_bucket_total{bucket="gt_10"} 8789
telemt_pool_swap_total 127
telemt_pool_force_close_total 3692
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 415
telemt_me_draining_writers_reap_progress_total 39758
telemt_me_writer_removed_unexpected_total 996
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3421
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37354
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3454
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36066
telemt_me_writer_teardown_success_total{mode="normal"} 40775
telemt_me_writer_teardown_noop_total 39770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80545
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 34.892014
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80545
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 415
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 935
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 4938889
telemt_user_connections_current{user="hello"} 2559
telemt_user_octets_from_client{user="hello"} 137343045855 (127.91 GB)
telemt_user_octets_to_client{user="hello"} 2260096904039 (2.06 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1058
telemt_user_unique_ips_recent_window{user="hello"} 329
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 118427.7 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21233658
telemt_connections_bad_total 1799882
telemt_connections_current 3866
telemt_connections_me_current 3866
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 647318
telemt_upstream_connect_attempt_total 210341
telemt_upstream_connect_success_total 191675
telemt_upstream_connect_fail_total 16757
telemt_upstream_connect_attempts_per_request{bucket="1"} 208432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9874
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16757
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65472
telemt_me_reconnect_success_total 2538
telemt_me_reader_eof_total 1582
telemt_me_idle_close_by_peer_total 1581
telemt_me_route_drop_no_conn_total 40082525
telemt_me_route_drop_channel_closed_total 130
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17056937
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 924
telemt_me_single_endpoint_outage_enter_total 153
telemt_me_single_endpoint_outage_exit_total 153
telemt_me_single_endpoint_outage_reconnect_attempt_total 322
telemt_me_single_endpoint_outage_reconnect_success_total 80
telemt_me_single_endpoint_quarantine_bypass_total 322
telemt_me_single_endpoint_shadow_rotate_total 934
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 33056
telemt_desync_full_logged_total 9971
telemt_desync_suppressed_total 23085
telemt_desync_frames_bucket_total{bucket="1_2"} 7214
telemt_desync_frames_bucket_total{bucket="3_10"} 14670
telemt_desync_frames_bucket_total{bucket="gt_10"} 11172
telemt_pool_swap_total 122
telemt_pool_force_close_total 3916
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 866
telemt_me_draining_writers_reap_progress_total 37290
telemt_me_writer_removed_unexpected_total 2361
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5056
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34343
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3358
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 558
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33374
telemt_me_writer_teardown_success_total{mode="normal"} 39399
telemt_me_writer_teardown_noop_total 37317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76716
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 218.329742
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76716
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 866
telemt_me_refill_failed_total 3813
telemt_me_writer_restored_same_endpoint_total 1722
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 17196369
telemt_user_connections_current{user="hello"} 3866
telemt_user_octets_from_client{user="hello"} 251524814229 (234.25 GB)
telemt_user_octets_to_client{user="hello"} 1329999548903 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 409002
telemt_user_msgs_to_client{user="hello"} 794272
telemt_user_unique_ips_current{user="hello"} 1567
telemt_user_unique_ips_recent_window{user="hello"} 548
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 118395.2 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6416358
telemt_connections_bad_total 611310
telemt_connections_current 2914
telemt_connections_me_current 2914
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 135679
telemt_upstream_connect_attempt_total 63072
telemt_upstream_connect_success_total 62340
telemt_upstream_connect_fail_total 626
telemt_upstream_connect_attempts_per_request{bucket="1"} 62966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26054
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 626
telemt_me_reconnect_attempts_total 69919
telemt_me_reconnect_success_total 1889
telemt_me_reader_eof_total 1661
telemt_me_idle_close_by_peer_total 1660
telemt_me_route_drop_no_conn_total 2473977
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4990880
telemt_me_endpoint_quarantine_total 805
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 901
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
telemt_me_writers_active_current 42
telemt_desync_total 24879
telemt_desync_full_logged_total 8722
telemt_desync_suppressed_total 16157
telemt_desync_frames_bucket_total{bucket="1_2"} 4917
telemt_desync_frames_bucket_total{bucket="3_10"} 9606
telemt_desync_frames_bucket_total{bucket="gt_10"} 10356
telemt_pool_swap_total 123
telemt_pool_force_close_total 3520
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 416
telemt_me_draining_writers_reap_progress_total 41828
telemt_me_writer_removed_unexpected_total 1697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4227
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39330
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3114
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38308
telemt_me_writer_teardown_success_total{mode="normal"} 43557
telemt_me_writer_teardown_noop_total 41829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85386
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.265241
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85386
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 416
telemt_me_refill_failed_total 4214
telemt_me_writer_restored_same_endpoint_total 1576
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 4982938
telemt_user_connections_current{user="hello"} 2914
telemt_user_octets_from_client{user="hello"} 129436133428 (120.55 GB)
telemt_user_octets_to_client{user="hello"} 2071596071638 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1257
telemt_user_unique_ips_recent_window{user="hello"} 386
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 55231.1 (15h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4428337
telemt_connections_bad_total 183815
telemt_connections_current 2262
telemt_connections_me_current 2262
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1752379
telemt_upstream_connect_attempt_total 31918
telemt_upstream_connect_success_total 31705
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 31911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12341
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_reconnect_attempts_total 46101
telemt_me_reconnect_success_total 1036
telemt_me_reader_eof_total 727
telemt_me_idle_close_by_peer_total 727
telemt_me_route_drop_no_conn_total 1113651
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2191155
telemt_me_endpoint_quarantine_total 396
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 430
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
telemt_desync_total 11843
telemt_desync_full_logged_total 4061
telemt_desync_suppressed_total 7782
telemt_desync_frames_bucket_total{bucket="1_2"} 2286
telemt_desync_frames_bucket_total{bucket="3_10"} 4532
telemt_desync_frames_bucket_total{bucket="gt_10"} 5025
telemt_pool_swap_total 60
telemt_pool_force_close_total 1761
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 154
telemt_me_draining_writers_reap_progress_total 20532
telemt_me_writer_removed_unexpected_total 797
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1759
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19600
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1552
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 209
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18771
telemt_me_writer_teardown_success_total{mode="normal"} 21359
telemt_me_writer_teardown_noop_total 20534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41893
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.699269
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41893
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 154
telemt_me_refill_failed_total 2618
telemt_me_writer_restored_same_endpoint_total 924
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2193513
telemt_user_connections_current{user="hello"} 2262
telemt_user_octets_from_client{user="hello"} 58677839904 (54.65 GB)
telemt_user_octets_to_client{user="hello"} 961649858854 (895.61 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1006
telemt_user_unique_ips_recent_window{user="hello"} 348
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 36202.1 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257256
telemt_connections_bad_total 1935
telemt_connections_current 479
telemt_connections_me_current 479
telemt_handshake_timeouts_total 6673
telemt_upstream_connect_attempt_total 17516
telemt_upstream_connect_success_total 17472
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 17512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 420
telemt_me_reconnect_success_total 241
telemt_me_reader_eof_total 241
telemt_me_idle_close_by_peer_total 241
telemt_me_route_drop_no_conn_total 72281
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229413
telemt_me_endpoint_quarantine_total 351
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 314
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 1222
telemt_desync_full_logged_total 334
telemt_desync_suppressed_total 888
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 40
telemt_pool_force_close_total 891
telemt_me_writer_close_signal_drop_total 34
telemt_me_draining_writers_reap_progress_total 15855
telemt_me_writer_removed_unexpected_total 230
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1011
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15085
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 889
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14964
telemt_me_writer_teardown_success_total{mode="normal"} 16096
telemt_me_writer_teardown_noop_total 15855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31951
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.256936
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31951
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 34
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 209
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 229040
telemt_user_connections_current{user="hello"} 479
telemt_user_octets_from_client{user="hello"} 3842477212 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 141937785564 (132.19 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 118399.5 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7772941
telemt_connections_bad_total 772760
telemt_connections_current 2981
telemt_connections_me_current 2981
telemt_handshake_timeouts_total 221543
telemt_upstream_connect_attempt_total 46680
telemt_upstream_connect_success_total 46510
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 46643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_reconnect_attempts_total 1693
telemt_me_reconnect_success_total 909
telemt_me_reader_eof_total 903
telemt_me_idle_close_by_peer_total 903
telemt_me_route_drop_no_conn_total 2206373
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5797881
telemt_me_endpoint_quarantine_total 847
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 910
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
telemt_me_writers_active_current 43
telemt_desync_total 22651
telemt_desync_full_logged_total 7469
telemt_desync_suppressed_total 15182
telemt_desync_frames_bucket_total{bucket="1_2"} 5676
telemt_desync_frames_bucket_total{bucket="3_10"} 8223
telemt_desync_frames_bucket_total{bucket="gt_10"} 8752
telemt_pool_swap_total 131
telemt_pool_force_close_total 3491
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 411
telemt_me_draining_writers_reap_progress_total 42137
telemt_me_writer_removed_unexpected_total 866
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3288
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39742
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3403
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38646
telemt_me_writer_teardown_success_total{mode="normal"} 43030
telemt_me_writer_teardown_noop_total 42139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85169
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.004841
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85169
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 411
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 814
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 5772430
telemt_user_connections_current{user="hello"} 2981
telemt_user_octets_from_client{user="hello"} 114069020812 (106.24 GB)
telemt_user_octets_to_client{user="hello"} 2700722954460 (2.46 TB)
telemt_user_unique_ips_current{user="hello"} 1211
telemt_user_unique_ips_recent_window{user="hello"} 387
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 118396.2 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6760418
telemt_connections_bad_total 661243
telemt_connections_current 3115
telemt_connections_me_current 3115
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 183046
telemt_upstream_connect_attempt_total 62524
telemt_upstream_connect_success_total 62055
telemt_upstream_connect_fail_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 62464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25078
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 409
telemt_me_reconnect_attempts_total 5792
telemt_me_reconnect_success_total 1277
telemt_me_reader_eof_total 1147
telemt_me_idle_close_by_peer_total 1147
telemt_me_seq_mismatch_total 55
telemt_me_route_drop_no_conn_total 2262925
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5166685
telemt_me_endpoint_quarantine_total 936
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 907
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
telemt_me_writers_active_current 42
telemt_desync_total 21526
telemt_desync_full_logged_total 7165
telemt_desync_suppressed_total 14361
telemt_desync_frames_bucket_total{bucket="1_2"} 5413
telemt_desync_frames_bucket_total{bucket="3_10"} 7871
telemt_desync_frames_bucket_total{bucket="gt_10"} 8242
telemt_pool_swap_total 129
telemt_pool_force_close_total 3433
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 415
telemt_me_draining_writers_reap_progress_total 40699
telemt_me_writer_removed_unexpected_total 1160
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3843
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38073
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37266
telemt_me_writer_teardown_success_total{mode="normal"} 41916
telemt_me_writer_teardown_noop_total 40703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82619
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.698256
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82619
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 415
telemt_me_refill_failed_total 260
telemt_me_writer_restored_same_endpoint_total 999
telemt_me_writer_restored_fallback_total 73
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 5169276
telemt_user_connections_current{user="hello"} 3115
telemt_user_octets_from_client{user="hello"} 96892299061 (90.24 GB)
telemt_user_octets_to_client{user="hello"} 2236909161516 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1228
telemt_user_unique_ips_recent_window{user="hello"} 370
```